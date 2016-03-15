# Experiments
This repository contains a bunch of stand alone experiments I'm using to evaluate different technologies.

## Running these experiments

Most of these experiments require just a simple http server. I use the standard [http-server](https://www.npmjs.com/package/http-server) available via npm:

```
npm install -g http-server
```

Then when inside one of the folders just run to start the server and disable all caching

```
> http-server -c-1

Starting up http-server, serving ./
Available on:
  http://10.210.116.141:8080
  http://192.168.56.1:8080
  http://127.0.0.1:8080
Hit CTRL-C to stop the server
```

You can also use [live-server](https://www.npmjs.com/package/live-server) to get similar functionality but with automatic reloading when any of your served pages changes.

## The list

Here's an overall list of what's in here:
- [nadel-api-gateway-ts](nadel-api-gateway-ts) - An implementation of [Ben Nadel's ApiGateway example](http://www.bennadel.com/blog/3047-creating-specialized-http-clients-in-angular-2-beta-8.htm) using typescript
- [angular2-template](angular2-template) - A vanilla template used to create new Angular2 examples
