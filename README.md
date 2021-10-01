# Configure centos server using Nginx as reverse proxy for apache with php-fpm and mariadb

## 1. Requirements:

- Ansible

## 2. Install ansible

```sh
yum install epel-release
yum install ansible
```

## 3. Configure server

```sh
ansible-playbook playbook.yml
```
