 	1. Hosts.ini 
	set [play:vars] accordingly
   
    2. First run gp-bastion-playbook:
    ansible-playbook -i hosts.ini playbook.yml --ask-become-pass
    --> --ask-become-pass Passwortabfrage für sudoers file Änderungen

    3.) Setup Github Runner
        current environment names: play/eval/shared
        e.g.: ENVIRONMENT_NAME=eval