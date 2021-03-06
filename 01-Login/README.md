# Auth0 - Ember 2

## Install the Dependencies

Install all the necessary dependencies using npm and Bower.

```bash
npm install
bower install
```

## Provide your Auth0 Credentials

This sample uses the [Lock](https://auth0.com/lock) widget for authentication which requires the client ID and domain for your application. If you haven't already done so, [sign up](https://auth0.com/signup) for your free Auth0 account and retrieve your client ID and domain from the [dashboard](https://manage.auth0.com). Rename the `auth0-variables.js.example` file to `auth0-variables.js` and populate it with your credentials.

## Running the App

Ember provides a server for the application which can be accessed with the `start` command.

```bash
npm start
```

The app will be served at `localhost:4200`.

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 account

1. Go to [Auth0](https://auth0.com/signup) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.