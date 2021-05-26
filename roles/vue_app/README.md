# vue_app

Prepares the machine for an app made with VueJS.

## Vars

- project_name
- app_name
- domain
- api_domain
- locale
- stable_release
- main
- repo
- options
- auth
- tls (public|self)

When you use auth you have to create the corresponding `.htpasswd` by yourself under `/etc/apache2/`.

If you are using self-signed certs, upload them to `/etc/ssl/[DOMAIN]/fullchain.pem` and `/etc/ssl/[DOMAIN]/privkey.pem`.

## Scripts

For updating the app, there is an update script. It's located in the /opt dir.
