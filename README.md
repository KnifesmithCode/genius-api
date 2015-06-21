[![Build Status](https://travis-ci.org/jahrlin/genius-api.svg?branch=master)](https://travis-ci.org/jahrlin/genius-api)
# genius-api
node.js client for the [Genius API](https://docs.genius.com)

##installation
```
$ npm install genius-api --save
```

##usage
```JavaScript
var api = require('genius-api');
var genius = new api(process.env.GENIUS_CLIENT_ACCESS_TOKEN);
```

##tests
```
$ git clone https://github.com/jahrlin/genius-api.git
$ cd genius-api
$ GENIUS_CLIENT_ACCESS_TOKEN={ACCESS_TOKEN} mocha
```
