# airbnb-browser-shims <sup>[![Version Badge][2]][1]</sup>

Browser and JS language shims used by Airbnb.

Just require/import it, and the environment will be shimmed.

Included shims:
 - JS language shims from [airbnb-js-shims](https://github.com/airbnb/js-shims)
 - [ima-babel6-polyfill](https://www.npmjs.com/package/ima-babel6-polyfill) - fixes Babel 6 bugs with `super` calls in IE 9 and 10
 - [document.contains](https://developer.mozilla.org/en/docs/Web/API/Node/contains)
 - [webrtc-adapter](https://www.npmjs.com/package/webrtc-adapter) - A shim to insulate apps from WebRTC spec changes and browser prefix differences
 - [classlist-polyfill](https://www.npmjs.com/package/classlist-polyfill) - Element.prototype.classList polyfill (only in browsers)
 - [raf](https://www.npmjs.com/package/raf) - requestAnimationFrame polyfill for browsers and node

[1]: https://npmjs.org/package/airbnb-browser-shims
[2]: http://versionbadg.es/airbnb/browser-shims.svg
