Role Name
=========

Creates a new server admin user that will replace root, then disables root ssh login.

Requirements
------------

Requires access to the root account.

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
      - {
          role: oscbco.create_app_admin,
          useradmin: 'server-admin'
        }

License
-------

MIT

Author Information
------------------
website: oscbco.me