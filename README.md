ansible-role-openresty
=========

A simple role to install and configure openresty (nginx+lua support bundle).

Requirements
------------


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: sebamontini.ansible-role-openresty, tags: openresty, become: true }

License
-------

Apache

Author Information
------------------

Sebastian Montini.
twitter.com/sebamontini
