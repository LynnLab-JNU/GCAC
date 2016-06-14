
Availability of GCAC Modules
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The GCAC Modules are made available to users at different levels to support users from novice, intermediate or advanced bioinformatics and/or system administration background.

i) Provided as VirtualBox VM:-  
      The easiest means to get the GCAC modules is as a standalone VirtualBox VM [link]. 
      This require the users to download and import the VM to their VirtualBox environment. 

ii) Provided via Toolshed:-  
      The GCAC modules include a list of Galaxy tools/utilities. These Galaxy tools/utilities are made 
      available via Public Toolshed repository [link].  This require the users to install the individual 
      Galaxy tools/utilities directly to their Galaxy instance. The Users require administrative privileges 
      to install it in their Galaxy instances. 

      There is a list of system level dependencies that needs to be installed by the users in the host Galaxy instance. 
      This requires sudo privileges to install system level dependencies. 

iii) Provided as Ansible playbooks:- 
      The GCAC modules are made available via GCAC ansible playbook. The GCAC ansible playbook leverages ansible 
      configuration management tool for deploying GCAC modules along with the system level dependencies.

