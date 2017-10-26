# p6lin
# Linux server Deployment

The project is under Udacity FSND.
IP address :

139.59.67.9 or pulkitsharma.me

password for sudo : graderbhai

### It's a ubuntu instance with following packages installed
- python
- python-pip
- python-sqlalchemy
- postgresql
- psychopg2
- apache2
- wsgi mod
- flask
- oauth2client
- requests
- finger
- curl
- git
- nodejs

### grader user is given sudo access
### firewall is set
### remote password login is disabled
### Catalog app is located at /var/www/catalog

This server is serving :
1. my webpage at pulkitsharma.me
2. catalog application at catalog.pulkitsharma.me

## Steps for Configuration
1. Made sure all package lists are updated and upgraded.
- sudo apt-get update
- sudo apt-get upgrade
2. Installed above listed packages using apt-get
3. Changed the authentication methods to use RSA Keys only in /etc/ssh/sshd_config
4. Revoked the root login by editing same file.
5. Updated firewall using ufw command.
6. git cloned the catalog project
7. Set up virtual hosts and wsgi files.
8. Good to Go.
