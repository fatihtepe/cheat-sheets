## To list
`To list all local users you can use:`
```
cut -d: -f1 /etc/passwd
```

## To add
```To add a new user you can use:```

```
sudo adduser new_username
```
or
```
sudo useradd new_username
```
## To remove/delete
`To remove/delete a user, first you can use:`
```
sudo userdel username
```
`Then you may want to delete the home directory for the deleted user account :`
```
sudo rm -r /home/username
```
## To modify
`To modify the username of a user:`
```
usermod -l new_username old_username
```
`To change the password for a user:`
```
sudo passwd username
```
`To change the shell for a user:`
```
sudo chsh username
```
## Sudo

```Switch to thte superuser account```
```
sudo su
```
```Switch to the superuser account with root's environment```
```
sudo su -
```
```Switch to the username's account with the username's environment```
```
sudo su - username
```

## add a user to sudo group
```
- sudo su -
- adduser newusername
	New password:
	Retype password:
	Changin the user information for newusername
- gpasswd -a newusername sudo
```
```Remove sudo user from the sudo group```
```
gpasswd -d newusername sudo
```
## <a href="https://linuxize.com/post/how-to-set-and-list-environment-variables-in-linux/">Common Environment Variables</a><br>
```
PATH
USER
HOME
EDITOR
UID
TERM
SHELL
LANG
```
`Environment variables` are variables that are available system-wide and are inherited by all spawned child processes and shells.

`Shell variables` are variables that apply only to the current shell instance. Each shell such as `zsh` and `bash`, has its own set of internal shell variables.

* `env`– The command allows you to run another program in a custom environment without modifying the current one. When used without an argument it will print a list of the current environment variables.
* `printenv` – The command prints all or the specified environment variables.
* `set` – The command sets or unsets shell variables. When used without an argument it will print a list of all variables including environment and shell variables, and shell functions.
* `unset` – The command deletes shell and environment variables.
* `export` – The command sets environment variables.

`echo $VARIABLE` To display value of a variable
```
printenv LANG == echo $LANG
```
`unset VARIABLE` remove a variable<br>

`export VARIABLE=value` To set value of an environment variable.

## The PATH Variable
```
printenv PATH == echo $PATH
```
## Add a New DIRECTORY to  the PATH
```
export PATH=$PATH:/games/awesome
```

`Single Quotes` protects everything enclosed between two single quote marks.

`Double quote` protects everything enclosed between two double quote marks except $, ', "" and \.

`Backslash` use the backslash to change the special meaning of the characters or to escape special characters within the text such as quation marks.