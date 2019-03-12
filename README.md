# Useage

```bash
$ ansible-playbook install.yml
```

This repo is to demonstrate how ansible roles work. Note the tree structure.

Project was initialized by running: `ansible-galaxy init apache-role`. The `install.yml` file calls the role to do the tasks.

This playbook utilizes 2 roles: `php-webserver` and `apache-role`. The apache-role is a dependency of php-webserver, which is declared in the `php-webserver/meta/main.yml` file.
