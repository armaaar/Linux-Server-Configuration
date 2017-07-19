# Linux Server Project
This repository is for listing all information related to my submission in "Linux Server Configuration" Project in [Udacity](https://www.udacity.com).

## Main data required

* IP Address: 52.57.68.216
* SSH Port: 2200
* Website URL: [http://52.57.68.216.xip.io](http://52.57.68.216.xip.io/)

## Software installed

* finger
* apache2
* git
* python
* postgresql
* virtualenv

### Apache2 modules

* mod_wsgi

### Virtual Environment python packages
* Virtual environment was installed on `/usr/local/venv/`.
* All packages installed are listed in the [Items Catalog Project](https://github.com/armaaar/items-catalog).

## Configuration changes

### Configure Apache2 to serve the website

Edited `/etc/apache2/sites-available/000-default.conf` to:
* Set path to virtual environment
* Serve the python .wsgi file to start the python app
* Serve static files through the server


### General changes

* Add custom user to sodoers
* Set up SSH keys
* Set timezone to UTC
* Change SSH port from 22 to 2200
* Configuration Uncomplicated Firewall (UFW) to only allow ports: 2200, 80, 123

## Acknowledgement

Thanks to [Google](http://www.google.com/) and [StackOverFlow](https://stackoverflow.com/) for guiding me through the entire process.
