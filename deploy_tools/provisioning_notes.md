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
ÃÄÄÄfunctional_tests
ÃÄÄÄdeploy_tools
³   ÀÄÄÄ__pycache__
ÃÄÄÄlists
³   ÃÄÄÄmigrations
³   ³   ÀÄÄÄ__pycache__
³   ÃÄÄÄstatic
³   ³   ÀÄÄÄbootstrap
³   ³       ÃÄÄÄcss
³   ³       ÃÄÄÄfonts
³   ³       ÀÄÄÄjs
³   ÃÄÄÄtemplates
³   ÀÄÄÄ__pycache__
ÀÄÄÄsuperlists
    ÀÄÄÄ__pycache__
