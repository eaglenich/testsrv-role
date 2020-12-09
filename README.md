testsrv deploy ansible role
=========

Purpose is to deploy (install, update, delete) testsrv microservice


Role Variables
--------------

`version` -- version of the microservice (1.0.0/1.0.1/etc)

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - testsrv-role
```
