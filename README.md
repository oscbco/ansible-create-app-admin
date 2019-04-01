Role Name
=========

Creates a new admin user that will replace root. Disables root ssh login.

Requirements
------------

Requires a access to the root account.

Role Variables
--------------

useradmin: The name of the new user

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
    roles:
      - {role: oscbco.disable_root_login, useradmin: 'app-admin'}

License
-------

MIT

Author Information
------------------

oscbco.dev