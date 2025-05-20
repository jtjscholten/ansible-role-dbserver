# Ansible Role: dbserver

Deze Ansible role installeert een MariaDB-server op Debian/Ubuntu-systemen, maakt een database aan en voegt een gebruiker toe.

## Variabelen

```yaml
mysql_root_password: "rootpassword"
mysql_user: "dbuser"
mysql_password: "dbpassword"
mysql_database: "webapp"
