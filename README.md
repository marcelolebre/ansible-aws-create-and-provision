# Ansible Scripting
1. Substitute all the ```<blah-blah>``` throughout the script as they refer to the specificities of your project

2. Execute ansible script

```
ansible-playbook  provisioning.yml -i localhost, --private-key=~/.ssh/<your_certificate.pem>
```  

3. Change files:  
	* APP_ROOT/.env 
	* APP_ROOT/config/database.yml
	* APP_ROOT/config/secrets.yml
