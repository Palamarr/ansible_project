1. Create dynamic inventory gcp.yml
2. Download gold-setup-485310-g8-cc25d296ac33.json with acount date, for use it in gcp.yml
3. Create config file, where add inventore file for ansible
(inventory = ./inventory/gcp.yml)
4. Create directory group_vars, add file all.yml, where i put ansible-user
and ssh-file. All this, made for connection to the servers
5. Tried ping command, and its works
6. Create directory roles, where are all roles.
create here common, docker roles
7. Common role: install basic packages, create servise user with crypted pass
8. Docker role: install apt repo for docker, packages for docker and docker
