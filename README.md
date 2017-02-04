#Holberton Assignment Checker

###My interpreation of the Holberton assignment checker. Not a web app, everything is done in the command line. 

##Run Instructions
1) run the setup to save your github username so the checker can grab the file on your github

`./setup`

2) navigate to the project folder and the task you want to check.

IE: `cd /holbertonschool-sysadmin_devops/0x00-shell_basics/0-current_working_directory1

3) run the checker file

`./checker`

The checker initially checks to see if the requirements are me. IE: Does the repo have a readme file, is the file only 2 lines long, etc.

If those check, it runs your command and the correct command and sees if the two outputs match. Currently there are a lot of issues with this setup so I've only written 2 test cases. But looking to fix this in the near future.

If you script's output passes all of the requirements and match the output of the correct command, then you get a Sucess, if not, you get a fail. In the future, ideally, the checker will return where your script failed.
