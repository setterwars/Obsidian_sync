# Access Control & Text File processing

## Users groups and premissions 
* Root(UID = 0)
* Regular user(UID >= 1000)
* Server User(Like "regular", but cannot directly login)
```
$less /etc/passwd

<username> : <password> : <UID> : <GID> : <GECOS> : <home_directory> : <shell>

```
sudo, su.

sudo - run a command as another user.
su requires you to know the user's password, including root.
```
$usseradd <username> - create a new user 

$usermod <username> - modify a user add the user to the supplementary group

$id <username> - print user group IDs

$sudo less /etc/shadow

$chage <username> - modify /etc/shadow in interactive mode 
```
## Controll access
```
$Chown user[:group] <file_name> - change file's user-owner and group-onwer 
$chgrp <group> <filename> - change file's group-owner

$chmod <mode> <filename> - change file premmisions.
```
## umask - default access rights configuration

umask - configures the shell to manage file or directory creation rights.

```
$umaske [mode] - set/display umask value, e.g. 0022
```

By default linux allocate premmisions as 666.

