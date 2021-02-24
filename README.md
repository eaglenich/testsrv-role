testsrv deploy ansible role
=========

Purpose is to deploy (install, update, delete) testsrv microservice


Role Variables
--------------

`version` -- version of the microservice (1.0.0/1.0.1/etc)
`service_name` -- service name
`user_name` -- user name
`group_name` -- group name

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - testsrv-role
```
