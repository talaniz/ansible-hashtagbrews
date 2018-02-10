# ansible-hashtagbrews
My Ansible playbook for deploying Hashtagbrews to a DigitalOcean droplet.

## Process
* Create new group and user
* Create new home directory
* Setup passwordless login based on ssh key
* `Manual`: Login, change default ssh port, disable root ssh login
* Install Python pre-requisites
* Setup Django project
* Setup Gunicorn, Nginx, certificates

## Ubuntu Setup
The basic Ubuntu setup is designed and tested for 16.04, taken from the [article provided by DigitalOcean](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04)
