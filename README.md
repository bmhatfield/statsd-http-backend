statsd-http-backend
===================

POSTS Data in JSON List format to an HTTP Backend

installation
============

   npm install statsd-graphite-http-backend

usage
=====

In config.js:  

```
{
backends: [ "statsd-graphite-http-backend" ],
api_key: 'YOUR CONFIGURED API KEY',
bridgeURL: 'http://GRAPHITE_SERVER:HTTP_PORT/publish/'
}
```

notes
=====

Should work with both [Backstop](https://github.com/obfuscurity/backstop) and [Graphite HTTP Bridge](https://github.com/bmhatfield/graphite-http-bridge)
