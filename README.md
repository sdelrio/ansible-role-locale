Ansible locale
==============

Set locale on system

Requirements
------------

No modules required.


Role Variables
--------------

`locale_list`: A list with the locales you want on the system.

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
    - hosts: servers
      roles:
        - role: locale
          vars:
            locale_list:
              - es_ES.UTF-8
              - es_ES
```

License
-------

BSD

