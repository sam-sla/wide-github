Wide Github
===========

This plugin changes all github repository pages to be full width and dynamically sized. Gists are supported as of version 1.1.0.

This repository always contains the latest version, the Chrome Store may not have been updated as recently.

Installing
----------

As a Chrome Extension:

This chrome extension can be installed from the [Chrome Web Store](https://chrome.google.com/webstore/detail/wide-github/kaalofacklcidaampbokdplbklpeldpj)

As a Greasemonkey / UserScript:

This script can be installed into Greasemonkey or other user script plugins by going here: [wide-github.user.js](https://raw.githubusercontent.com/xthexder/wide-github/master/build/wide-github.user.js)

As a Stylus / UserCSS

This style can be installed into Stylus by going here: [wide-github.user.css](https://raw.githubusercontent.com/xthexder/wide-github/master/build/wide-github.user.css)

Development
-----------

To generate the user.js for Greasemonkey, run `make js`. The user.css can be built using `make css`. The chrome extension can be built using `make chrome`.

Personalization
-------------

The size of the margins can be modified if you don't like the default 20px as it can look too wide on wide-screens/resolutions. Increasing this value will make the margins larger and therefore reduce the width of the github interface.
Modify the defaults `margin-left: 20px` and `margin-right: 20px` to, for example, 300px, in the source you're using (i.e, [wide-github.user.js](https://raw.githubusercontent.com/xthexder/wide-github/master/build/wide-github.user.js) for the UserScript and [wide-github.user.css](https://raw.githubusercontent.com/xthexder/wide-github/master/build/wide-github.user.css) for the UserCSS).
