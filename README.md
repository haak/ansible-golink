Role Name
=========

This role is used to deploy Tailscale golink using docker
https://github.com/tailscale/golink/

Requirements
------------

Docker should be installed on the host

Role Variables
--------------

docker_home:
golink_data_directory:
golink_authkey:

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         -  golink

License
-------

BSD

Author Information
------------------

Alex Kelleher Github.com/haak
