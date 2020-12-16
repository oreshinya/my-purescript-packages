# My PureScript Packages

PureScript packages maintained currently by oreshinya.

## Frontend

### [purescript-grain](https://github.com/purescript-grain/purescript-grain)

A UI library with easy and flexible state management inspired by [Recoil.js](https://recoiljs.org/) and [React Hooks](https://reactjs.org/docs/hooks-intro.html). No npm dependencies required.

If you are looking for something instead of Halogen, react-basic and so on, I recommend it.

It has examples and guide already, so you can start to learn it.

### [purescript-grain-router](https://github.com/purescript-grain/purescript-grain-router)

Router for [purescript-grain](https://github.com/purescript-grain/purescript-grain).

### [purescript-grain-virtualized](https://github.com/purescript-grain/purescript-grain-virtualized)

The virtual list to render huge list efficiently for [purescript-grain](https://github.com/purescript-grain/purescript-grain).

If you encount performance problem of huge VDOM, you should use this.


### [purescript-freedom](https://github.com/purescript-freedom/purescript-freedom)

A practical type-safe UI library for PureScript. No npm dependencies required.

It has examples and guide already, so you can start to learn it.

### [purescript-freedom-router](https://github.com/purescript-freedom/purescript-freedom-router)

Router subscription for purescript-freedom.

### [purescript-freedom-portal](https://github.com/purescript-freedom/purescript-freedom-portal)

A way to render children into a node that exists outside the DOM hierarchy of the parent node.

It helps you implementing UI like modal, dropdown, and so on.

### [purescript-freedom-transition](https://github.com/purescript-freedom/purescript-freedom-transition)

An easy way to perform animations when a purescript-freedom view enters or leaves the DOM.

It helps you implementing animations when enters/leaves of elements.

### [purescript-freedom-virtualized](https://github.com/purescript-freedom/purescript-freedom-virtualized)

The virtual list to render huge list efficiently for purescript-freedom.

If you encount performance problem of huge VDOM, you should use this.

### [purescript-freedom-window-resize](https://github.com/purescript-freedom/purescript-freedom-window-resize)

Subscription of resizing window for purescript-freedom.

It's for observing to resize window.

### [purescript-freedom-now](https://github.com/purescript-freedom/purescript-freedom-now)

Subscription to get current time for purescript-freedom.

### [purescript-identy](https://github.com/oreshinya/purescript-identy)

An opinionated UI state management utilities.

If you want to manage complex application state, it may help you.

It has guide, so you can know an idea of purescript-identy.

## Backend

### [purescript-bucketchain](https://github.com/Bucketchain/purescript-bucketchain)

A PureScript webserver interface based on asynchronous middlewares.

This is just a interface to implement middlewares.

### [purescript-bucketchain-simple-api](https://github.com/Bucketchain/purescript-bucketchain-simple-api)

A simple RPC style API middleware of Bucketchain.

Its features are type-level routing, authentication, batch operation, and so on.

If you are tired RESTful API, you may like this.

### [purescript-bucketchain-static](https://github.com/Bucketchain/purescript-bucketchain-static)

A static file server middleware of Bucketchain.

### [purescript-bucketchain-conditional](https://github.com/Bucketchain/purescript-bucketchain-conditional)

A conditional GET middleware of Bucketchain.

This manages only `Last-Modified`, not `Etag`.

### [purescript-bucketchain-history-api-fallback](https://github.com/Bucketchain/purescript-bucketchain-history-api-fallback)

A History API fallback middleware of Bucketchain.

### [purescript-bucketchain-secure](https://github.com/Bucketchain/purescript-bucketchain-secure)

Middlewares for Bucketchain to make apps secure by HTTP headers.

It includes the following:

- `X-Content-Type-Options`
- `X-Download-Options`
- `X-Frame-Options`
- `Strict-Transport-Security`
- `X-XSS-Protection`

### [purescript-bucketchain-sslify](https://github.com/Bucketchain/purescript-bucketchain-sslify)

A force https middleware of Bucketchain.

### [purescript-bucketchain-basic-auth](https://github.com/Bucketchain/purescript-bucketchain-basic-auth)

A basic authentication middleware of Bucketchain.

### [purescript-bucketchain-cors](https://github.com/Bucketchain/purescript-bucketchain-cors)

A CORS middleware of Bucketchain.

### [purescript-bucketchain-csrf](https://github.com/Bucketchain/purescript-bucketchain-csrf)

A Bucketchain middleware for stateless CSRF protection without token.

This middleware checks some headers:

- `Host`: Check if host(for DNS Rebinding).
- `X-From`: Check if allowed origin. you should send all request with this header.
- `Origin`: Check if allowed origin.

### [purescript-bucketchain-health](https://github.com/Bucketchain/purescript-bucketchain-health)

A healthcheck middleware of Bucketchain.

### [purescript-bucketchain-logger](https://github.com/Bucketchain/purescript-bucketchain-logger)

Logger middlewares of Bucketchain.

### [purescript-bucketchain-header-utils](https://github.com/Bucketchain/purescript-bucketchain-header-utils)

The HTTP header utilities of Bucketchain.

It has utilities for `Cookie` and `Vary` only.

### [purescript-crypto](https://github.com/oreshinya/purescript-crypto)

PureScript wrapper for `crypto` module of NodeJS.

### [purescript-basic-auth](https://github.com/oreshinya/purescript-basic-auth)

Basic authentication helper.

### [purescript-mysql](https://github.com/oreshinya/purescript-mysql)

Bindings [mysql](https://github.com/mysqljs/mysql) for PureScript.

### [purescript-nodemailer](https://github.com/oreshinya/purescript-nodemailer)

Bindings [nodemailer](https://github.com/nodemailer/nodemailer) for PureScript.

### [purescript-simple-jwt](https://github.com/oreshinya/purescript-simple-jwt)

Simple JWT(JSON Web Token) encoder and decoder for PureScript.

## Others

### [purescript-simple-ulid](https://github.com/oreshinya/purescript-simple-ulid)

A implementation of Universally Unique Lexicographically Sortable Identifier written with PureScript.

### [purescript-simple-emitter](https://github.com/oreshinya/purescript-simple-emitter)

PureScript simple event emitter.

### [purescript-simple-i18n](https://github.com/oreshinya/purescript-simple-i18n)

Type-safe internationalization utilities.

### [simple-rev](https://github.com/oreshinya/simple-rev)

Static asset revisioning.

It's a cli on npm, but written with PureScript.
