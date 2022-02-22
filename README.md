ToDo:

1. centos/redhat distro VM (amazon linux) - Done
2. setup ansible and the inventory to reach the server -Done
3. ansible tasks:

- set hostname - Done
  dont forget /etc/hosts (use template file) - Done

- update the OS packages automatically

- set up users and groups e.g.: user1 user2 user3 etc, groups example: devops, qa, dev - Done
  a user has: username, group, a home dir - Done
  disable password expiration
  copy their public ssh key to their homedir/.ssh/authorized_keys (example key is fine doesn't have to be a real key)
  add them into sudoers as ALL=(ALL) NOPASSWD: ALL
  add them into sshd_config AllowUsers (template file helpful)
