<p align="center"><img src="https://raw.githubusercontent.com/MonkeyGG2/VioletGG2-Static/main/public/uv.png" height="200"></p>

<h1 align="center">VioletGG2</h1>

An easily deployable version of MonkeyGG2 with a built-in proxy, powered by [Ultraviolet](https://github.com/titaniumnetwork-dev/Ultraviolet).

# Deployment

> ## BEWARE ❗❗❗
>
> Some of the following services may shut down your proxy application because proxies violate their TOS. Notable examples include:
>
> - Replit
> - Glitch
> - Railway
> - Heroku

[![Deploy to Heroku](https://binbashbanana.github.io/deploy-buttons/buttons/official/heroku.svg)](https://heroku.com/deploy/?template=https://github.com/MonkeyGG2/VioletGG2)
[![Run on Replit](https://binbashbanana.github.io/deploy-buttons/buttons/official/replit.svg)](https://replit.com/github/MonkeyGG2/VioletGG2)
[![Remix on Glitch](https://binbashbanana.github.io/deploy-buttons/buttons/official/glitch.svg)](https://glitch.com/edit/#!/import/github/MonkeyGG2/VioletGG2)
[![Deploy to IBM Cloud](https://binbashbanana.github.io/deploy-buttons/buttons/official/ibmcloud.svg)](https://cloud.ibm.com/devops/setup/deploy?repository=https://github.com/MonkeyGG2/VioletGG2)
[![Deploy to Amplify Console](https://binbashbanana.github.io/deploy-buttons/buttons/official/amplifyconsole.svg)](https://console.aws.amazon.com/amplify/home#/deploy?repo=https://github.com/MonkeyGG2/VioletGG2)
[![Run on Google Cloud](https://binbashbanana.github.io/deploy-buttons/buttons/official/googlecloud.svg)](https://deploy.cloud.run/?git_repo=https://github.com/MonkeyGG2/VioletGG2)
[![Deploy to Oracle Cloud](https://binbashbanana.github.io/deploy-buttons/buttons/official/oraclecloud.svg)](https://cloud.oracle.com/resourcemanager/stacks/create?zipUrl=https://github.com/MonkeyGG2/VioletGG2/archive/refs/heads/main.zip)
[![Deploy on Railway](https://binbashbanana.github.io/deploy-buttons/buttons/official/railway.svg)](https://railway.app/new/template?template=https://github.com/MonkeyGG2/VioletGG2)
[![Deploy to Koyeb](https://binbashbanana.github.io/deploy-buttons/buttons/official/koyeb.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/MonkeyGG2/VioletGG2&branch=main&name=deploy-buttons)
[![Deploy to Render](https://binbashbanana.github.io/deploy-buttons/buttons/official/render.svg)](https://render.com/deploy?repo=https://github.com/MonkeyGG2/VioletGG2)
[![Deploy to Cyclic](https://binbashbanana.github.io/deploy-buttons/buttons/official/cyclic.svg)](https://app.cyclic.sh/api/app/deploy/MonkeyGG2/VioletGG2)

### Deploying to Another Service

If you are deploying to an alternative service or to a server, then follow these steps:

- ```shell
  git clone --recursive https://github.com/MonkeyGG2/VioletGG2
  ```
- Edit the config for `/VioletGG2-Static/public/MonkeyGG2/config.jsonc` like this:

```jsonc
{
  // ... games and other stuff
  "config": {
    // don't change any part of the config other than the following lines, unless you know what you are doing
    "proxy": true,
    "proxyPath": "/proxy.html"
    // ... other config
  }
}
```

- Refer to [Deploy via terminal](https://github.com/titaniumnetwork-dev/Ultraviolet-App/wiki/Deploy-via-terminal).

Additional information regarding Ultraviolet can be found on Titanium-Network's [wiki](https://github.com/titaniumnetwork-dev/Ultraviolet-App/wiki).
