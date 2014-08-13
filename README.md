Licensr
=======

License your projects with a nice CLI tool!

[![Dependencies Status][gemnasium-image]][gemnasium-url] [![Build Status][travis-image]][travis-url] [![Code quality][codeclimate-image]][codeclimate-url] [![Code coverage][coveralls-image]][coveralls-url] [![Release][npm-image]][npm-url]

[![ruche logo](https://raw.githubusercontent.com/quentinrossetti/licensr/master//assets/animated.gif)](https://github.com/quentinrossetti/licensr)

Usage
---

Just run `licensr` an follow the guide!

You can also use *Licensr* as a node module. You can use super greats 
*Promises* or you can stick with the node's callbacks.

```js
var licensr = require('licensr');
licensr.command('git config --get user.name')
  .then(function (username) {
    // on fulfill
    console.log(username);
  }, function (err) {
    // on reject
    console.error(err);
  });
```


Installation
---

Configure your git environement and install *Licensr* as global node module.


```bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
npm install -g licensr
```
[gemnasium-url]: https://gemnasium.com/quentinrossetti/licensr
[gemnasium-image]: http://img.shields.io/gemnasium/quentinrossetti/licensr.svg
[travis-url]: https://travis-ci.org/quentinrossetti/licensr
[travis-image]: http://img.shields.io/travis/quentinrossetti/licensr.svg
[codeclimate-url]: https://codeclimate.com/github/quentinrossetti/licensr
[codeclimate-image]: http://img.shields.io/codeclimate/github/quentinrossetti/licensr.svg
[coveralls-url]: https://coveralls.io/r/quentinrossetti/licensr
[coveralls-image]: http://img.shields.io/coveralls/quentinrossetti/licensr.svg
[npm-url]: https://www.npmjs.org/package/licensr
[npm-image]: http://img.shields.io/npm/v/licensr.svg