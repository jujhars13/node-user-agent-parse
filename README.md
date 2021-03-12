# Node User Agent Parse

Very simple, no deps user agent string parser.

[![NPM](https://nodei.co/npm/user-agent-parse.png?downloads=true)](https://nodei.co/npm/user-agent-parse/)
[![Build Status](https://travis-ci.org/jujhars13/node-user-agent-parse.png?branch=master)](https://travis-ci.org/jujhars13/node-user-agent-parse)

## Overview

Parse user agents a bit like PHP's [get_browser()](http://php.net/manual/en/function.get-browser.php).
Rudimentary but it works.

## Example Usage

```javascript
const userAgent = require('user-agent-parse');
userAgent.parse('Mozilla/5.0 (Windows; U; Windows NT 5.1; en) AppleWebKit/526.9 (KHTML, like Gecko) Version/4.0dp1 Safari/526.8');
// => { name: 'safari', version: '4.0dp1', os: 'Windows XP', full: '... same string as above ...', device_type:'desktop' }
```

## Tests

See `/test/test.js` for a simple suite

## Credits

Heavily based on (blatantly ripped from *ahem*) https://github.com/soldair/node-ua-device-type and https://github.com/jujhars13/node-user-agent-parse

## License

License is [MIT](LICENCE.md), go nuts.
