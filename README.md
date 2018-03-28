Role Name
=========

This is java installation and configuration role.

Requirements
------------
No requirements for this role.

Role Variables
--------------

The variables of this roles are: 
  - java_rpm_repo: This is the java RPM repository url  for RedHat systems by default it is for java 10 and  it can be overrided.
  - debian_java_repo: This the Debian java repository url

Dependencies
------------
 No dependancies

Example Playbook
----------------
This is an exemple of haw we can use this role:


    - hosts: servers
      roles:
         - { role: WissemChb.java, java_rpm_repo: oracle_bse_url/java_version/jdk*.rpm , debian_java_repo: debian repo }

License
-------

BSD

#Author Information
------------------

#An optional section for the role authors to include contact information, or a website (HTML is not allowed).
