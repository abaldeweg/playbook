# abaldeweg.playbook

Installs some basic roles for machines that run php and JavaScript apps.

## Requirements

- Ubuntu 18.04

## Roles

More about the roles in their corresponding readme.

- apt
- php
- certbot
- apache
- mysql
- composer
- reboot
- git

## Vars

More about the vars in the corresponding readme for the role.

- mysql
- symfony_app
- vue_app

## Getting Started

Install the collection.

```shell
ansible-galaxy collection install abaldeweg.playbook
```

Then, add the roles to your playbook e.g. `abaldeweg.playbook.apt` and set the vars.

### Deploy the Config

Run the playbook.

Configure your MySQL Server with the following command.

```shell
mysql_secure_installation
```

Now you can (re-)install your certificates. If you wanna use Let's Encrypt all you need is already installed. Just run the following command and get the certificates.

```shell
certbot certonly --apache
```

Run the playbook again, so the vHosts can be activated.

Reboot your system.
