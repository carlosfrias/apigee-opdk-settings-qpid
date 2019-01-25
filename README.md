Apigee OPDK Settings Qpid
=========

The purpose of this role is to expose Qpid ports to playbooks that work on the Apigee platform.

Requirements
------------

N/A

Role Variables
--------------

    qpid_jmx_port: 1102
    qpid_int_mgmt_port: 4529
    qpid_messaging_port: 5672
    qpid_ext_mgmt_port: 8083

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: qpid
      roles:
         - { role: apigee-opdk-settings-qpid }

License
-------

Apache 2.0

Author Information
------------------

Carlos Frias