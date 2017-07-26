# hubot-brain-redis-hash

[![Build Status](https://travis-ci.org/halkeye/hubot-brain-redis-hash.svg?branch=master)](https://travis-ci.org/halkeye/hubot-brain-redis-hash)
[![NPM](https://nodei.co/npm/hubot-brain-redis-hash.png)](https://nodei.co/npm/hubot-brain-redis-hash/)

Hubot brain that uses hset and hget instead of storing everything as one giant blob

## Getting Started
1. Install the module: `npm install --save hubot-brain-redis-hash`
2. Add `hubot-brain-redis-hash` to the first entry of your external-scripts.json file in your hubot directory
This may be necessary as it temporarily unloads redis brain, an other external scripts may not load or save the necessary data.
3. Profit

## Configuration (optional)
```
export REDISTOGO_URL="redis://localhost:6379"
```

## Release History

0.1.3 - 2016-09-10

* Added REDIS_PREFIX env config - Thanks @erikzaadi

## License
Copyright (c) 2013 Gavin Mogan
Licensed under the MIT license.
