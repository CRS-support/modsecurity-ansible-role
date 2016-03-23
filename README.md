ModSecurity
=====

This role can install and uninstall ModSecurity on an Apache webserver.
It is the offical working repository of the ModSecurity team. If you
have suggestions or constructive feedback, please provide it here.

Requirements
------------

This role requires Ansible 2.0 or higher and either a debian or redhat based OS

Examples
========

Install ModSec:
```ansible-playbook modsecurity.yaml --tags "modsec_install"```

Install CRS:
```ansible-playbook modsecurity.yaml --tags "crs_install"```

Uninstall CRS:
```ansible-playbook modsecurity.yaml --tags "crs_uninstall"```

Uninstall ModSec:
```ansible-playbook modsecurity.yaml --tags "modsec_uninstall"```



License
-------
Apache

Author Information
------------------
Chaim Sanders

