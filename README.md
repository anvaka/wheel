# wheel  [![Build Status](https://travis-ci.org/anvaka/wheel.svg)](https://travis-ci.org/anvaka/wheel)

This module unifies handling of mouse whee event across different browsers.

See [MDN](https://developer.mozilla.org/en-US/docs/Web/Reference/Events/wheel?redirectlocale=en-US&redirectslug=DOM%2FMozilla_event_reference%2Fwheel)
for more details.

# Usage

``` js
var addWheelListener = require('wheel').addWheelListener;
var removeWheelListener = require('wheel').removeWheelListener;
addWheelListener(domElement, function (e) {
	// mouse wheel event
});
removeWheelListener(domElement, function);
```

You can also use a shortcut for addWheelListener:

``` js
var addWheelListener = require('wheel');
addWheelListener(domElement, function (e) {
	// mouse wheel event
});
```

# install

With [npm](https://npmjs.org) do:

```
npm install wheel
```

# license

MIT
