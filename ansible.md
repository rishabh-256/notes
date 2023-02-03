ansible-vault create vault.yml
ansible-vault edit vault.yml
ansible-vault decrypt vault.yml
ansible-playbook --ask-vault-pass vault.yml
ansible-vault rekey vault.yml


ansible-vault create --vault-id password@prompt vault.yml 
