# rexec
a remote script executor  
executes commands over ssh, using the options supplied.
###Usage
```
rexec [-rh] [-h hosts] [-s script] [-c certificate] [hosts] [positional parameters]
Options: 
       	-r     		execute commands using sudo  
       	-h     		shows usage (this) and exits  
       	-H     		list of hosts to connect to  
       	-s     		the script to execute  
       	-c     		a certificate to use for authentication  
       	-u     		the user to log in as, defaults to ec2-user  
```
All options can be supplied as a file or as a string


##Installation
https://github.com/Gherkin/homebrew-tap
```
$ brew tap Gherkin/tap
$ brew install rexec
```
