Ansible docker Role for Debian
==============================

Features:
---------
* installes dockerd from offical repo
* zfs storage driver possible 

Supported Platforms:
--------------------
- Debian stretch


Usage:
------
Create a variable declaration on a host basis along the following:

```yaml
docker_storage_driver: zfs
```
