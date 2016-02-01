MongoDB
=======

Installs and configures a single-host MongoDB service

Requirements
------------

None

Role Variables
--------------

```
- mongodb_bind_addresses:
    - 127.0.0.1
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      become: yes
      roles:
        - role: ryanlelek.mongodb
          mongodb_bind_addresses:
            - 127.0.0.1
            - 11.22.33.44
            - 55.66.77.88

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
