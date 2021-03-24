 	1. Hosts.ini 
	set [play:vars] accordingly
   
    2. Erstmaliges Ausführen playbook:
    ansible-playbook -i hosts.ini playbook.yml --ask-become-pass
    --> --ask-become-pass Passwortabfrage für sudoers file Änderungen 