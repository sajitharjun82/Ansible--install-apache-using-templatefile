Ansible
Ansible is an open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code..

About install-apache-ubuntu-amazon.yml
Using this Ansible playbook, we can install apache in a Redhat and Debian based Linux box. After installing the apache, Ansible will place a sample index file in the document root of the apache, and apache loads the index file.

Also enabled the Apache service in run levels

About website-setup.yml
Using this Ansible playbook, we can install Nginx in a Debian based Linux box and it uploads the website files to the document root of the Nginx from the local system. Then it starts the Nginx service and Nginx will serve the uploaded website contents.
