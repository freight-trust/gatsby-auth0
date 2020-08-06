# Auth0 Gatsby
[![Build Status](https://travis-ci.com/freight-trust/gatsby-auth0.svg?branch=master)](https://travis-ci.com/freight-trust/gatsby-auth0)


This is an updated version from the sample application for the Auth0 tutorial on [Securing Gatsby with Auth0](https://auth0.com/blog/securing-gatsby-with-auth0/). It is based on the [official Gatsby hello-world starter](https://github.com/gatsbyjs/gatsby-starter-hello-world).

### Modify auth config

Rename `.env.EXAMPLE` to `.env.development` (or `.env.production`) and replace `<value>` for `AUTH0_DOMAIN` and `AUTH0_CLIENTID` with your Auth0 domain prefix and your client ID. These can be found on your [client dashboard](https://manage.auth0.com/#/clients).

Replace the `<value>` for `AUTH0_CALLBACK` with the URL for your callback route. The default for development is `http://localhost:8000/callback`.

## Run the app
You can start the development server with the following command:

```bash
gatsby develop
```

The app runs at `localhost:8000` by default.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at the auth0-blog repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

SEE CONTRIBUTORS
[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
