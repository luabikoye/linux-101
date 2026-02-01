# Users & Groups

## User Management
- `adduser username` → Add user
- `passwd username` → Set password
- `userdel username` → Delete user
- `userdel -r username` → Delete user + home

## Group Management
- `groupadd groupname` → Create group
- `groupdel groupname` → Delete group
- `usermod -aG groupname username` → Add user to group

## Switch Users
- `su - username` → Switch to another user
- `who` → Current logged-in users
- `whoami` → Current user
- `last` → Show last logins
