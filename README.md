# Awesome Micro [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img align="right" src="https://camo.githubusercontent.com/67335088cb7b156fb779f6d60635e70780efe714/68747470733a2f2f636c6475702e636f6d2f4a446d6d4858337568462e737667" />

A collection of awesome things regarding zeit's [Micro](https://github.com/zeit/micro) — Async ES6 HTTP microservices.

## Modules

- Routing
  - [fs-router](https://github.com/jesseditson/fs-router) - Use the FS as your micro router.
  - [micro-api](https://github.com/possibilities/micro-api) - Minimal routing layer for building JSON APIs.
  - [micro-route](https://github.com/dotcypress/micro-route) - Tiny http routing helper.
  - [micro-router](https://github.com/pedronauck/micro-router) - A tiny and functional router for Zeit's Micro.
  - [micro-method-router](https://github.com/jamo/micro-method-router) - Minimal routing layer for HTTP methods.
- [micro-compress](https://github.com/joakimbeng/micro-compress) - Compression for HTTP microservices.
- [micro-cors](https://github.com/possibilities/micro-cors) - Simple CORS middleware.
- [micro-github](https://github.com/mxstbr/micro-github) - Add authentication with GitHub to your application.
- [micro-boom](https://github.com/onbjerg/micro-boom) - Wraps errors in [`micro`](https://github.com/zeit/micro) services [`Boom`](https://github.com/hapijs/boom) errors.
- [micro-gallery](https://github.com/andreasmcdermott/micro-gallery) - Like zeit's list, but for images.
- [micro-analytics](https://github.com/mxstbr/micro-analytics) - Public analytics as a Node.js microservice, no sysadmin experience required.
- [micro-stats](https://github.com/dotcypress/micro-stats) - Statsd helper for Micro.
- [micro-visualize](https://github.com/onbjerg/micro-visualize) - Development tool that visualizes requests and responses for services written with Micro.
- [micro-stats](https://github.com/dotcypress/micro-stats) - Statsd helper for Micro.
- [micro-chain](https://github.com/dimapaloskin/micro-chain) - Builds flexible requests chains and pass them into micro handler.
- [microauth](https://github.com/microauth) - Collection of authentication modules for zeit's micro.
- [micro-cookie-session](https://github.com/billymoon/micro-cookie-session) - Simple cookie-based session storage for micro.
- [micro-ratelimit](https://github.com/dotcypress/micro-ratelimit) - Rate limiting middleware for Micro.
- [micro-get](https://github.com/romuloalves/micro-get) - Only accepts GET request for microservices built with Micro.
- [micro-post](https://github.com/romuloalves/micro-post) - Only accepts POST request for microservices built with Micro.
- [micro-jwt-auth](https://github.com/kandros/micro-jwt-auth) - json web token(jwt) authorization wrapper for Micro.

## Development Tools

- [generator-micro-service](https://github.com/vadimdemedes/generator-micro-service) - Yeoman generator to kick-start your microservice with `micro` and `ava`
- [create-micro](https://github.com/romuloalves/create-micro) - a generator for `micro` projects
- [micro-starter](https://github.com/samtgarson/micro-starter) - Basic (opinionated) starter kit for a micro app with webpack build
- [micro-cluster](https://github.com/zeit/micro-cluster) - Run multiple micro servers and a front proxy at a time
- [dev-gateway](https://github.com/dimapaloskin/dev-gateway) - Local development gateway with [path aliases](https://zeit.co/docs/features/path-aliases) support.

## Articles & FAQ

- [Minimum Viable Async with Node 6](https://gist.github.com/rauchg/8199de60db48026a6670620a1c33b700)
- [Regarding no-middleware](https://github.com/zeit/micro/issues/8)
- [Use Micro with routes](https://github.com/zeit/micro/issues/16#issuecomment-193518395)

## Built with Micro

- [Serve](https://github.com/zeit/serve) - Static file serving and directory listing.
- [now-go](https://github.com/amio/now-go) - A personal tinyurl service.
