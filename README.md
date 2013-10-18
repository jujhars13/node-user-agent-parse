# NodeJs User Agent Parse

[![NPM](https://nodei.co/npm/user-agent-parse.png?downloads=true)](https://nodei.co/npm/user-agent-parse/)

## Overview

Parse user agents a bit like PHP's [get_browser()](http://php.net/manual/en/function.get-browser.php)

## Example
```javascript
     var userAgent = require('user-agent')
     userAgent.parse('Mozilla/5.0 (Windows; U; Windows NT 5.1; en) AppleWebKit/526.9 (KHTML, like Gecko) Version/4.0dp1 Safari/526.8')
     // => { name: 'safari', version: '4.0dp1', os: 'Windows XP', full: '... same string as above ...', device_type:'desktop' }
```
## Credits

Heavily Based (Blatantly ripped from *ahem*) on https://github.com/soldair/node-ua-device-type and https://github.com/jujhars13/node-user-agent-parse

## TODO
Test using mocha

##License

License is [MIT](http://opensource.org/licenses/mit-license.php), go nuts. That's how we roll here at [Buto](http://get.buto.tv).

