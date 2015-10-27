proxify
=========

Role for configuring package managers for proxies

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - {
	 role: andrewrothstein.proxify,
	 proxy_env : { http_proxy : 'http://localhost:3128/' }
	 }

License
-------

MIT

Author Information
------------------

Andrew Rothstein
andrew.rothstein@gmail.com
https://github.com/andrewrothstein
