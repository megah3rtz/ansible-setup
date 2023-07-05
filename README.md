# ansible-setup
Ansible setup for VMs

get ippsec's parrot build playbooks

# git clone https://github.com/IppSec/parrot-build.git

Add 1password to the list of firefox plugins
# echo '  - "1password-x-password-manager"' > parrot-build/roles/customize-browser/vars/main.yml

Add extra vscode extensions
- HashiCorp.terraform
- Bridgecrew.checkov > parrot-build/main.yml

get a sudo token
# sudo whoami

Install the galaxy roles
# ansible-galaxy install -r requirements.yml

run the ippsec playbook
# ansible-playbook main.yml

run the personal playbook
# ansible-playbook main.yml --ask-vault-pass

setup 1password
# sh ~/.1passwordsetup.sh