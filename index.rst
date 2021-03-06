.. title:: Introduction to Nutanix AHV

.. toctree::
  :maxdepth: 2
  :caption: Technology Overview (Read Only)
  :name: _technology_overview
  :hidden:

  what_is_nutanix/what_is_nutanix
  nutanix_terminology/nutanix_terminology
 
.. toctree::
  :maxdepth: 2
  :caption: Entry level - Nutanix Configuration Labs
  :name: _nutanix_configuration_labs
  :hidden:

  lab_nutanix_tech_overview/lab_nutanix_tech_overview
  lab_storage_configuration/lab_storage_configuration
  lab_network_configuration/lab_network_configuration

.. toctree::
  :maxdepth: 2
  :caption: Entry level - Deploying and Managing Workloads
  :name: _deploying_and_managing_workloads
  :hidden:

  backup_and_dr/backup_and_dr(Read Only)
  lab_deploy_workloads/lab_deploy_workloads
  lab_manage_workloads/lab_manage_workloads
  lab_data_protection/lab_data_protection

.. toctree::
  :maxdepth: 2
  :caption: Entry level - Monitoring and Managing the Environment
  :name: _monitoring_and_managing_the_environment
  :hidden:

  monitoring_and_managing_env/monitoring_and_managing_env
  lab_monitoring_env/lab_monitoring_env

.. toctree::
  :maxdepth: 2
  :caption: Advanced level - Self Service Portal
  :name: _optional_labs
  :hidden:

  authentication/authentication
  ssp/ssp
 

.. toctree::
  :maxdepth: 2
  :caption: Advanced level - Files
  :name: _optional_files_labs
  :hidden:
  
  files_deploy/files_deploy
  files_smb_share/files_smb_share
  files_nfs_export/files_nfs_export

.. toctree::
  :maxdepth: 2
  :caption: Advanced level - Flow Lab
  :name: _optional_flow_lab
  :hidden:

  what_is_flow/what_is_flow
  flow_enable/flow_enable
  flow_quarantine_vm/flow_quarantine_vm
  flow_isolate_environments/flow_isolate_environments
  flow_secure_app/flow_secure_app
  flow_visualization/flow_visualization

.. toctree::
  :maxdepth: 2
  :caption: Advanced level - Calm Lab
  :name: _optional_calm_lab
  :hidden:

  what_is_calm/what_is_calm
  calm_enable/calm_enable
  calm_projects/calm_projects
  calm_sshkey_creation/calm_sshkey_creation
  calm_mysql_blueprint/calm_mysql_blueprint
  calm_3twa_blueprint/calm_3twa_blueprint
  calm_windows_blueprint/calm_windows_blueprint
  calm_marketplace/calm_marketplace



.. toctree::
  :maxdepth: 2
  :caption: Appendix
  :name: _appendix
  :hidden:

  appendix/glossary
  appendix/basics

.. _getting_started:

---------------
Getting Started
---------------

Welcome to the Nutanix .Next On Tour Hong Kong Hands-on Lab Session. Let's get your hands dirty !

**Open Time:** 12:45 pm - 3:00 pm

This workbook introduces Nutanix technologies and many common management tasks. Each section has a lesson and an exercise to give you hands-on practice. By Attending, you will:

- understand the **basic concepts** and **advanced technologies** that make up the Nutanix Enterprise Cloud stack.
- Get a souvenir  by completing an advanced level lab or two entry level labs
- Stand a chance to win an DJI Trello at the Hands-on Lab Lucky Draw at **3:00 pm**.

Agenda
++++++

- Workshop updated for the following software versions:
    - AOS & PC 5.9.2

- Entry level labs
    - Nutanix Configuration 
    - Deploying and Managing Workloads
    - Monitoring and Managing the Environment

- Advanced level labs
    - Self Service Portal
    - Files
    - Flow (Micro-segmentation)
    - Calm (Multi-clouds automation)

.. note::

  Some sub-tasks are "deploy" or "enable", which can only be performed once. You may just take a look of our "one-click-deploy" design philosophy and proceed to the next tasks.
    
    
How to Access
+++++++++++++

All of these clusters are located in U.S. and you may access it through a HTML 5 broswer using VDI.

.. note::

  The VDI login credential is unique to each individuals and do not kick other people out of their session.
  https://citrixready.nutanix.com  Or  https://hostedpoc.nutanix.com - *Accessible via HTML5*



.. list-table::
  :widths: 10 10 20 20
  :header-rows: 1
  
  * - Seat Number 
    - Cluster Name
    - VDI login
    - VDI password
  * - 1
    - POC041
    - POC041-User01
    - partnerSE/4u
  * - 2
    - POC041
    - POC041-User02
    - partnerSE/4u     
  * - 3
    - POC041
    - POC041-User03
    - partnerSE/4u    
  * - 4
    - POC041
    - POC041-User04
    - partnerSE/4u
  * - 5
    - POC041
    - POC041-User05
    - partnerSE/4u
  * - 6
    - POC044
    - POC044-User01
    - partnerSE/4u
  * - 7
    - POC044
    - POC044-User02
    - partnerSE/4u  
  * - 8
    - POC044
    - POC044-User03
    - partnerSE/4u
  * - 9
    - POC044
    - POC044-User04
    - partnerSE/4u    
  * - 10
    - POC044
    - POC044-User05
    - partnerSE/4u    
  * - 11
    - POC045
    - POC045-User01
    - partnerSE/4u    
  * - 12
    - POC045
    - POC045-User02
    - partnerSE/4u        
  * - 13
    - POC045
    - POC045-User03
    - partnerSE/4u        
  * - 14
    - POC045
    - POC045-User04
    - partnerSE/4u        
  * - 15
    - POC045
    - POC045-User05
    - partnerSE/4u         
  * - 16
    - POC046
    - POC046-User01
    - partnerSE/4u       
  * - 17
    - POC046
    - POC046-User02
    - partnerSE/4u       
  * - 18
    - POC046
    - POC046-User03
    - partnerSE/4u       
  * - 19
    - POC046
    - POC046-User04
    - partnerSE/4u      
  * - 20
    - POC046
    - POC046-User05
    - partnerSE/4u       
  * - 21
    - POC048
    - POC048-User01
    - partnerSE/4u      
  * - 22
    - POC048
    - POC048-User02
    - partnerSE/4u    
  * - 23
    - POC048
    - POC048-User03
    - partnerSE/4u    
  * - 24
    - POC048
    - POC048-User04
    - partnerSE/4u    
  * - 25
    - POC048
    - POC048-User05
    - partnerSE/4u    



After you have logged into the VDI ...
++++++++++++++++++++++++++++++++++++++


Hosted POC clusters follow a standard naming convention:

- **Cluster Name** - POC\ *XYZ*
- **Subnet** - 10.**21**.\ *XYZ*\ .0
- **Cluster IP** - 10.**21**.\ *XYZ*\ .37

For example:

- **Cluster Name** - POC055
- **Subnet** - 10.21.55.0
- **Cluster IP** - 10.21.55.37

Throughout the Workshop there are multiple instances where you will need to substitute *XYZ* with the correct octet for your subnet, for example:

.. list-table::
   :widths: 25 75
   :header-rows: 1

   * - IP Address
     - Description
   * - 10.21.\ *XYZ*\ .37
     - Nutanix Cluster Virtual IP
   * - 10.21.\ *XYZ*\ .39
     - **PC** VM IP, Prism Central
   * - 10.21.\ *XYZ*\ .40
     - **DC** VM IP, NTNXLAB.local Domain Controller

Each cluster is configured with 2 VLANs which can be used for VMs:

.. list-table::
  :widths: 25 25 10 40
  :header-rows: 1

  * - Network Name
    - Address
    - VLAN
    - DHCP Scope
  * - Primary
    - 10.21.\ *XYZ*\ .1/25
    - 0
    - 10.21.\ *XYZ*\ .50-10.21.\ *XYZ*\ .124
  * - Secondary
    - 10.21.\ *XYZ*\ .129/25
    - *XYZ1*
    - 10.21.\ *XYZ*\ .132-10.21.\ *XYZ*\ .253

Credentials
...........

.. note::

  The *<Cluster Password>* is unique to each cluster and will be provided by the leader of the Workshop.

.. list-table::
   :widths: 25 35 40
   :header-rows: 1

   * - Credential
     - Username
     - Password
   * - Prism Element
     - admin
     - partnerSE/4u
   * - Prism Central
     - admin
     - partnerSE/4u
   * - Controller VM
     - nutanix
     - partnerSE/4u
   * - Prism Central VM
     - nutanix
     - partnerSE/4u

Each cluster has a dedicated domain controller VM, **DC**, responsible for providing AD services for the **NTNXLAB.local** domain. The domain is populated with the following Users and Groups:

.. list-table::
   :widths: 25 35 40
   :header-rows: 1

   * - Group
     - Username(s)
     - Password
   * - Administrators
     - Administrator
     - nutanix/4u
   * - SSP Admins
     - adminuser01-adminuser25
     - nutanix/4u
   * - SSP Developers
     - devuser01-devuser25
     - nutanix/4u
   * - SSP Power Users
     - poweruser01-poweruser25
     - nutanix/4u
   * - SSP Basic Users
     - basicuser01-basicuser25
     - nutanix/4u



