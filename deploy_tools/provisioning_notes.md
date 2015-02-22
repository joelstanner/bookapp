Provisioning a new site
=======================


## Required packages:

* nginx
* Python 3
* Git
* pip
* virtualenv

eg, on CentOS:

    sudo yum install nginx git python3 python3-pip
    sudo pip3 install virtualenv (or just use python3's pyvenv)
    
## Nginx Virtual Host config

* see nginx.template.conf
* replace SITENAME with, eg, staging.my-domain.com

## Folder structure:
Assume we have a user account at /home/username 

/home/username
└── sites
    └── SITENAME
         ├── database
         ├── source
         ├── static
         └── virtualenv
