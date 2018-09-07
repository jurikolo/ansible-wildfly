# ansible-wildfly
Playground for automated Wildfly deployment with Ansible

Master branch is empty, checkout branches named based on Wildfly version

## Prerequisites
Before playbook is executed, following actions must be made:
* user ansible exists (useradd ansible)
* user ansible is part of sudoers group (usermod -aG wheel ansible)

Optional:
* allow ansible user to sudo without password (sudo visudo --> ansible ALL=(ALL) NOPASSWD:ALL)