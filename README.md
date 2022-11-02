# slapd.me
Installs docker and sets up 3 containers
 1. OpenLdap https://hub.docker.com/r/osixia/openldap
 2. phpLdapAdmin https://hub.docker.com/r/osixia/phpldapadmin
 3. Ldap Account Manager https://hub.docker.com/r/ldapaccountmanager/lam


Asks for Organization name, ldap domain and admin password through console input  

ORGANIZATION NAME (whatever you want)  
LDAP DOMAIN (your domain: my.domain.com)  
PASSWORD (Same password will be used in all services)  

Simply make slapd.me executable and run it with sudo.

Docker container names are:
- phpldapadmin-service
- ldap-service
- lam-service

To start/stop the services use:
- docker start phpldapadmin-service ldap-service lam-service
- docker stop phpldapadmin-service ldap-service lam-service

![alt text](https://pics.freeicons.io/premium/hand-slap-slapping-pictogram-icon-124063-256.png)

