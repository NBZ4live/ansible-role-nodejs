nodejs
=========

This role installs nodejs, npm and additional global packages optionally.

Requirements
------------

This role requires Ansible 1.4 or higher and tested platforms are listed in the metadata file.

Role Variables
--------------

The role uses the following variables:

 - **nodejs_apt_packages**: The list of packages to be installed by the
  ```apt```, defaults to ```[nodejs-legacy,npm]```.
   module.
 - **nodejs_packages_global**: A list of npm packages to install, defaults to ```[]```  

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: nbz4live.nodejs }

License
-------

BSD

Author Information
------------------

- Sergey Fayngold
