<p align="center">
  <img src="./assets/logo.png">
</p>

## zeit-secrets-integration

This allows you to manage your secrets on `zeit.co`.

This Application only uses the [zeit.co api](https://zeit.co/docs/api/) and does **not** safe any of your secret data!

**Marketplace**: [https://zeit.co/integrations/secrets](https://zeit.co/integrations/secrets)

### How to use?

1. Login into [zeit.co](https://zeit.co/)
2. Open [https://zeit.co/integrations/secrets](https://zeit.co/integrations/secrets)
3. Click on the **ADD** Button at the upper right corner
4. Choose your account/team
5. Now find it in your [Integrations Dashboard](https://zeit.co/dashboard/integrations)
6. Click on **Untitled Configuration** and edit all your secrets (:

### Screenshots

<p align="center">
  <img src="./assets/screen1.png">
</p>

<p align="center">
  <img src="./assets/screen2.png">
</p>

<p align="center">
  <img src="./assets/screen3.png">
</p>

<p align="center">
  <img src="./assets/screen4.png">
</p>

### Development

First add **[now-cli](https://github.com/zeit/now-cli)**

```bash
yarn add global now # or npm install -g now
```

Create an Integration at the [Integration Console](https://zeit.co/dashboard/integrations/console) and insert all necessary data.
Set the **UI Hook URL** to **http://localhost:5005** and **Privacy** to **Private**.
After clicking **CREATE**, you will see the **VIEW IN MARKETPLACE** button in the upper right corner.


Click it and run the following

```bash
yarn # or npm install
#
yarn dev # start the dev server on port 5005
```

If the server is running, reload your integration page.
