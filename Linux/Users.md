
Super admin = root

Servers will give you a root user, and a random password for you to connect, or an IT guy will give you an user like `jubuli` and a password like `chaduli1`


to change the password of a user you either put 
```
passwd <user>
```

or 

```
passwd
```
to default to the current user

to add a new user
```
adduser <new-user>
```

to grant sudo privileges to the user
```
adduser jubuli sudo
```

to switch to the a different user
```
su <user>
```


