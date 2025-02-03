# Access Control & Text File processing

## Users groups and premissions 
* Root(UID = 0)
* Regular user(UID >= 1000)
* Server User(Like "regular", but cannot directly login)

$less /etc/passwd
<username> : <password> : <UID> : <GID> : <GECOS> : <home_directory> : <shell>

sudo, su.

sudo - run a command as another user.
su requires you to know the user's password, including root.

$usseradd <username> - create a new user 
$usermod <username> - modify a user add the user to the supplementary group
$id <username> print user group IDs

$sudo less /etc/shadow
