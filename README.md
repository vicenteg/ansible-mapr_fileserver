mapr_fileserver
========

Installs mapr-fileserver.

Requirements
------------


Role Variables
--------------

```
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: http://1.2.3.4:3128
```


Dependencies
------------


Example Playbook
-------------------------

```
- hosts: fileserver
  roles:
    - mapr_fileserver
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com
