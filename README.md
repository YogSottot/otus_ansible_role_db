DB role for Otus ![Build Status](https://travis-ci.com/YogSottot/otus_ansible_role_db.svg?branch=master)
=========

Install MongoDB for reddit app. Otus homework.

Role Variables
--------------

```db_mongo_bind_ip:``` Set the ip that Mongo will use.  
```db_mongo_port:``` Set the port that Mongo will use.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: db
      roles:
         - { role: db }

License
-------

WTFPL

Author Information
------------------

YogSottot
