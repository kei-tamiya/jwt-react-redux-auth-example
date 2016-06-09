# jwt-react-redux-auth-boilerplate

It is the boilerplate of authentication using JWT in the SPA of React-Redax.
It doesn't support server-side rendering.

## Get started

```bash
$ git clone git@github.com:nabeliwo/jwt-react-redux-auth-boilerplate.git

$ cd jwt-react-redux-auth-boilerplate
$ npm install
$ npm run build-js # build bundle.js
```

In order to launch the server, and then prepare a config file.

```json
// config/default.json

{
  "host": "127.0.0.1",
  "secretKey": "your secret key"
}
```

```bash
# run
$ npm run dev # to develop
# Server running at: http://localhost:3000

# develop
$ npm run watch-js # watchify
$ npm run lint # eslint
```

## Detail