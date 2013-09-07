remote_expect
=============

expect script which ends user in interact mode - interact can be switched off and command enabled followed by uncommenting last few lines in order automate password driven ssh connection 


to get a script going you need to

    sudo-apt-get install expect or 
    sudo yum install expect


This running:

      whoami
			myuser
			./ssh-connect.exp localhost
			spawn ssh myuser@localhost
			myuser@localhost's password: 
			Welcome to Ubuntu 12.04.2 LTS (GNU/Linux XXXX)
			
			 * Documentation:  https://help.ubuntu.com/
			
			Last login: Sat Sep  7 20:19:53 2013 from localhost
			sudo bash
			This is BASH 4.2- DISPLAY on localhost:0.0
			
			Sat Sep  7 20:25:09 BST 2013
			whoami
			[20:25 myuser@myuser-DP ~] > sudo bash
			whoami
			This is BASH 4.2- DISPLAY on localhost:0.0
			
			Sat Sep  7 20:25:09 BST 2013
			[20:25 myuser@myuser-DP ~] > whoami
			root
			[20:25 myuser@myuser-DP ~] > whoami
			root
