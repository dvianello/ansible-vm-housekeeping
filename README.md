vm-housekeeping
=========

A role to carry out housekeeping works before snapshotting a VM to create an image, heavily inspired by this [post](https://lonesysadmin.net/2013/03/26/preparing-linux-template-vms/) at _lonesysadmin.com_. Currently used to bake packer builds!


Requirements
------------
See `meta/main.yml`.

None.

Role Variables
--------------
See `defaults/main.yml`.

Dependencies
------------
None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vm-housekeeping

License
-------
Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
