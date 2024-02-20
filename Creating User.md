# Creating a User

ubuntu@ip:~/ansible/playbooks$ cat create_user.yml
---
- name: This Playbook will create a user
hosts: all
become: true
tasks:
- name: Create a user Your name
user: name=Your name
