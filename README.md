# cmpe272-HW1-ansible
CMPE 272 - Homework #1 - Ansible
install.yml : Install epel-repo, nginx, enables port 8080, sets 8080 port configuration for nginx
portset.conf: Configuration file used to set port as 8080 so that http://198.18.134.49:8080 and http://198.18.134.50:8080 will direct to webpage.
hosts -  Servers are defined here
ansible.cfg : overwrites the default ansible.cfg to use hosts file for server information.
index.html : html file that prints “Hello World from centosX” where X is 1 or 2 depending on which webserver.
uninstall.yml : Stops nginx service and then removes it.
