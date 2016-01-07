# p5_server_config
Project 5 for Udacity Full Stack Web Dev Nanodegree

## Server Access Information
# Note:Server access has been disable with completion of Udacity nanodegree
* IP addess: 52.33.246.117
* SSH port: 2200
* URL to catalog app:
http://ec2-52-33-246-117.us-west-2.compute.amazonaws.com/

default password for user: grader is provided in the "Notes to Reviewr" field.

## Configuration Changed
* ran apt-get update and upgrade
* UFW only allows traffic on port 2200, 80, and 123
* root user remote login disabled
* user: grader added to sudoers
* key-based ssh authentication required, password login disabled
* ssh hosted on port 2200
* timezone changed to UTC

## Software installed(updated)
* unattended-upgrades: for managing package updates automatically
* Apache: for hosting Catalog App
* libapache2-mod-wsgi: for hosting Catalog App
* Postgresql: for Catalog App DB requirement
* NTP: for time sync
* fail2ban: to monitor and prevent repeated unsuccessful login
* Glances: for system monitoring

## Python packages installed (for Catalog App)
* flask
* sqlalchemy
* oauth2client
