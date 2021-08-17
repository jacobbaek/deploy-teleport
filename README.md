# teleport deploy playbook
deploy teleport proxy/auth and teleport node via ansible playbook

# What is teleport and understading what the teleport works
* https://mr100do.tistory.com/1287 (written in Korean)

# prerequites
require 3 nodes.
* node1 : run teleport proxy/auth 
* node2 : run teleport node #1
* node3 : run teleport node #2

# How to do
1. check group_vars
   (have to change the auth_server ip address that will run as teleport auth server)
2. check inventory/hosts.ini
3. run the ansible-playbook
