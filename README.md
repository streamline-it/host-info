Role Name
=========

host-info

Requirements
------------
None

Role Variables
--------------

host_info_text_directory: /root

host_info_facts_directory: /etc/ansible/facts.d

host_info_text_filename: hostinfo.txt
host_info_fact_filename: hostinfo.fact

# enumerate all applied roles
host_info_roles_applied:
  - 

# change as needed, for example in a FreeBSD system this will be wheel
host_info_root_group: root

host_info_ansible_dev: 
host_info_ansible_dev_email_address:
host_info_initial_config_date: 03/03/2025

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - host-info
or
  
     - hosts: servers
       tasks:
         - name: import_role
           import_role:
             name: host-info
           

License
-------

BSD

Author Information
------------------


