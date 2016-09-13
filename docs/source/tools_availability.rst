
Availability of GCAC Modules
=============================

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


1. GCAC VirtualBox VM
-----------------------

The GCAC "VirtualBox VM" is a standalone machine with pre-installed Galaxy and "GCAC modules" along with all the 
system-level/GCAC-modules dependencies. 


2. GCAC Toolshed Repository
-----------------------------

The GCAC "toolshed repository" is a standard method to make available Galaxy tools/utilities. These can be easily 
installed by a Galaxy administrator via Galaxy Admin interface of Galaxy instance.  


3. GCAC Ansible Playbook
---------------------------

The GCAC “ansible playbooks” are automated means to install the complete system from the scratch. 
Although this method is fully automated but it requires understanding of ansible which is a 
configuration management (CM) tool for deploying applications, managing app configuration and orchestration. 

The GCAC ansible playbook uses “ansible role” [see what is an ansible role?]  to perform specific tasks 
such as installation of application and system level dependencies/packages, management of application 
configurations, etc. We have used publically available “ansible roles” [link to galaxy project ansible roles] 
and customized it to make available the GCAC modules.

The installation steps are divided into three levels to support specific computing infrastructure requirements 
of users. Each of these steps is powered by specific ansible roles. Users need to understand these steps to 
fully leverage the power of “ansible roles” and “ansible playbooks”.  

**The Installation Steps**

| 1. OS preparation for the Galaxy Instance.
| 2. Installation and configuration of the Galaxy Application.
| 3. Installation of the GCAC Galaxy Modules and system level dependencies/packages. 
|

  .. note:: 

    | 1. The first two steps are for the new installation of Galaxy instances. 
    | 2. The third step is for the installation of GCAC Galaxy modules on new/existing Galaxy instances.
    | 
