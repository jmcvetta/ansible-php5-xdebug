PHP XDebug
=========

Ansible role to enable XDebug support in PHP.


Requirements
------------

Ubuntu 14.04LTS


Role Variables
--------------

```yaml
php_installations:
  - apache2
  - cli

# Output folder for Xdebug profiler (undefined by default)
php_profiler_dir: 

# Autostart debugger
php_debug_autostart: no
```


Dependencies
------------

n/a


Example Playbook
----------------

    - hosts: web:&dev
      roles:
         - jmcvetta.php5-xdebug


License
-------

This is Free Software, released under the terms of the Aapche v2 license.  See
http://www.apache.org/licenses/LICENSE-2.0 for details.  Resist intellectual
serfdom - the ownership of ideas is akin to slavery.


Author Information
------------------

[Jason McVetta](mailto:jason.mcvetta@gmail.com)
