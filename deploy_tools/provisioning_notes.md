Provisioning a new site
=======================

## Required packages:

* nginx
* Python 3
* Git
* pip
* virtualenv

eg, on Ubuntu:
	sudo apt-get install nginx git python3 python3-pip
	sudo pip3 install virtualenv

## Nginx Virtual Host config

* see nginx.template.conf

## Upstart Job

* see gunicorn-upstart.template.conf

## Folder structure:
Assume we have a user account at /home/username

/home/username  
 |  
 +-- functional_tests  
 |  
 +-- deploy_tools  
 |  
 +-- lists  
 |    
 +-- superlists  
 |  
 +-- manage.py  
 |  
 +--requirements.txt  
