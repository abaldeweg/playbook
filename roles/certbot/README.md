# certbot

Installs the certbot from ppa.

## Config

If you wanna use Let's Encrypt all you need is already installed. Just run the following command and get the certificates.

```shell
certbot certonly --apache
```

Run the playbook again, so the vHosts can be activated.
