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
| Variable | Description | Default value |
|----------|-------------|---------------|
|`secure_deployment_user`| User that will be used for future deployments | `none` |

License
-------
BSD
