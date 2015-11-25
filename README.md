# Ansible Scripting

1. Execute ansible script

```
ansible-playbook  provisioning.yml -i localhost, --private-key=~/.ssh/<your_certificate.pem>
```  

2. Change files:  
	* APP_ROOT/.env 
	* APP_ROOT/config/database.yml
	* APP_ROOT/config/secrets.yml
