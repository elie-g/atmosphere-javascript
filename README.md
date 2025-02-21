## Welcome to Atmosphere: The Asynchronous WebSocket/Comet Framework
The Atmosphere Framework contains client and server side components for building Asynchronous Web Applications. The majority of [popular frameworks](https://github.com/Atmosphere/atmosphere/wiki/Atmosphere-PlugIns-and-Extensions) are either supporting Atmosphere or supported natively by the framework. The Atmosphere Framework supports all major [Browsers and Servers](https://github.com/Atmosphere/atmosphere/wiki/Supported-WebServers-and-Browsers)

Follow us on [Twitter](http://www.twitter.com/atmo_framework) or get the latest news [here](http://async-io.org)

Atmosphere transparently supports WebSockets, Server Sent Events (SSE), Long-Polling, HTTP Streaming (Forever frame) and JSONP.

* [npm/Node.js client](https://github.com/Atmosphere/atmosphere.js-node)
* [Browser client](https://raw.github.com/Atmosphere/atmosphere-javascript/master/modules/javascript/src/main/webapp/javascript/atmosphere.js)

## Install

### manually
You can get atmosphere.js in several ways. If you use a script tag whose src attribute is set to the below one, browser may not load it because the content type served by raw.github.com is text/plain.

* [atmosphere v3.1.3](https://raw.github.com/Atmosphere/atmosphere-javascript/javascript-project-3.1.3/modules/javascript/src/main/webapp/javascript/atmosphere.js)

Also it is available from the following places, but there may be delays between a release and its availability. We don't manage these ways officially but they are managed by open source community so you can contribute.
* NPM - [atmosphere.js](https://www.npmjs.com/package/atmosphere.js)
* WebJars - [atmosphere](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.webjars%22%20AND%20a%3A%22atmosphere-javascript%22)

If you need to support Inetrnet Explorer 7, Firefox 3.0, Safari 3 and Opera 10  and lower versions, a `JSON.stringify` / `JSON.parse` polyfill is henceforth required like:
https://github.com/bestiejs/json3

### maven

```xml
<dependency>
    <groupId>org.atmosphere.client</groupId>
    <artifactId>javascript</artifactId>
    <version>3.1.3</version>
</dependency>
```

### npm

```shell
npm install atmosphere.js
```

### bower

```shell
bower install atmosphere
```

## Docs
Full API documentation can be read [here](https://github.com/Atmosphere/atmosphere/wiki/atmosphere.js-API) and a lot of samples [here](https://github.com/Atmosphere/atmosphere-samples)

It is recommended to always use the version that matches Atmosphere's runtime.

Latest version may work with lower version, but not officially tested.

### Changelogs
* 3.1.x releases [3.1.0](https://github.com/Atmosphere/atmosphere-javascript/issues?q=is%3Aissue+is%3Aclosed+label%3A3.1.0)
