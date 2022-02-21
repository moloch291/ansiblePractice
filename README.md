ToDo:

1. centos/redhat distro VM (amazon linux)
2. setup ansible and the inventory to reach the server
3. ansible tasks:
- set hostname
dont forget /etc/hosts (use template file)

- update the OS packages automatically

- set up users and groups e.g.: user1 user2 user3 etc, groups example: devops, qa, dev
a user has: username, group, a home dir
disable password expiration
copy their public ssh key to their homedir/.ssh/authorized_keys (example key is fine doesnt have to be a real key)
add them into sudoers as ALL=(ALL) NOPASSWD: ALL
add them into sshd_config AllowUsers (template file helpful)
