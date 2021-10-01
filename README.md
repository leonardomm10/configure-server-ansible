# Configure centos server using Nginx as reverse proxy for apache with php-fpm and mariadb

-Requirements:

- Ansible

-Install ansible

```sh
yum install epel-release
yum install ansible
```

-Configure server

```sh
ansible-playbook playbook.yml
```
