---
{
  "context": "http://schema.org",
  "type": "Educational event",
  "duration": "P30M",
  "id": "20151001-nodejs-threading-mode",
  "name": "NodeJS threading mode",
  "layout": "page.html",
  "description": "This talk will explore the architecture of the threading model of NodeJS. In this model, the programmer works in a single threaded environment but leverages the asynchronous operations to system threads managed by the framework. This makes NodeJS very suitable for small services non CPU-bounded that communicate with external services or perform asynchronous operations, like querying a caching backend (memcached) or adding elements to a queue system.",
  "inLanguage": "en",
  "performer": {
    "type": "Person",
    "name": "Jordi Gomez",
    "id": "20151001-nodejs-threading-mode",
    "twitter": "jgomezb79",
    "sameAs": "https://twitter.com/@jgomezb79",
    "url": "/talk/20151001-nodejs-threading-mode.html",
    "image": "https://avatars2.githubusercontent.com/u/1548185?v=3&s=400"
  }
}
---
# NodeJS threading mode

This talk will explore the architecture of the threading model of NodeJS. In this model, the programmer works in a single threaded environment but leverages the asynchronous operations to system threads managed by the framework. This makes NodeJS very suitable for small services non CPU-bounded that communicate with external services or perform asynchronous operations, like querying a caching backend (memcached) or adding elements to a queue system.