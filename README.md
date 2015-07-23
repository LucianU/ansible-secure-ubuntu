secure
======

A role that secures a Ubuntu install. It:
 - creates a user for deployments and sets up the SSH key
 - hardens the SSH server
 - installs fail2ban
 - configures unattended upgrades
 - sets up iptables rules

Role Variables
--------------

`secure_deployment_user` - the user that will be used for future deployments

License
-------

BSD

Author Information
------------------

Lucian Ursu
