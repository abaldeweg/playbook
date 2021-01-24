# core

Prepares your machine for an app made with symfony.

## Vars

- domain
- repo
- jwt_passphrase
- app_name (used for vHost and db name)
- project_name
- mail
- stable_release
- app_secret
- mysql_user
- mysql_password
- db_host
- db_port
- cors_domain
- auth

When you use auth you have to create the corresponding `.htpasswd` by yourself under `/etc/apache2/`.

## Scripts

For updating the app, there is an update script. It's located in the /opt dir.
