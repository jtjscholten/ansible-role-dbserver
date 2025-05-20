# Ansible Role: dbserver

Deze Ansible role installeert MariaDB, maakt een database aan en voegt een gebruiker toe.

## Gebruik

```yaml
- hosts: dbservers
  become: true
  roles:
    - jtjscholten.dbserver
