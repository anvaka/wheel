# wheel  [![Build Status](https://travis-ci.org/anvaka/wheel.svg)](https://travis-ci.org/anvaka/wheel)

I don't think you need to use this library anymore. Use this instead:


``` js
  element.addEventListener('wheel', ...);
```

In 2014 this module was supposed to unify handling of mouse wheel event across
different browsers.

Now it's just a wrapper on top of `element.addEventListener('wheel', callback)`.

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
