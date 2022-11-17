# adyen-shopware6 Demo

- Create a new workspace: 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ayodejidev/adyen-shopware6)

- Wait for the "Unable to find a matching sales channel for the request" message to appear in the preview panel.
- Open a new terminal tab and run:

```
APP_DOMAIN=`gp url 8080 | sed 's~https://~~'` ./install.sh
```

- Visit your store at `$APP_DOMAIN/admin`
- Login with default Shopware Admin credentials: 
    * User: **admin**
    * Password: **shopware**
- Follow the remaining configuration steps (e.g. obtain API keys, enable payment methods) from our official [Shopware 6 Getting Started Guide](https://docs.adyen.com/plugins/shopware-6)