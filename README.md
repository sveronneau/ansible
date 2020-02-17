# ansible
Ansible brain dump that preps a CentOS (v7 prefedred) VM with tooling and XRDP.  also creates a local user and levereges andisble-vault to handle passing the password.

To generate the my_vault.yml file:
* ansible-vault create my_vault
* Enter your Vault password
* Then put this in the file
* my_password: you_password

the Ansible-Vault config is all commented right now.  Plz adjust to your needs.
