Install MySQL server.
Install Ansible and Vault.
Create Ansible roles for backup and restore.
Configure tasks and variables.
Encrypt sensitive information using Ansible Vault.
Create playbooks for backup and restore.
use "ansible-playbook -i hosts MysQL_Backup.yml --vault-password-file vault_pass"   ### give vault password in vault_pass
use  "ansible-playbook -i hosts MysQL_restore.yml --vault-password-file vault_pass" ### give vault password in vault_pass
