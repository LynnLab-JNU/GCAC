Description of GCAC Ansible Playbook
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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

| 1. OS preparation of Galaxy Instance.
| 2. Installation and configuration of Galaxy Application.
| 3. Installation of the GCAC Galaxy Modules and system level dependencies/packages. 
|

The first two steps are for the pristine installation of Galaxy instances. 
The third step is for the installation of GCAC Galaxy modules on any Galaxy instances.  

