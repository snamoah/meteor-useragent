## Meteor Package for detecting platform details ##

This is a meteor package that allows you to detect information about the platform your app is running on such as operating system version, browser information, etc. This is a wrapper of the [platform.js library](https://github.com/bestiejs/platform.js)

### Installation ###

```
$ meteor add snamoah:usergent
```

### Usage ###

```javascript
// to detect os properties of the device

var os = platform.os.family;     // returns OS name
var architecture = platform.os.architecture;     // return 64 or 32
var osVersion = platform.os.version;    // returns OS version NB: can return null



// to detect browser
var browser = platform.name;  // return browser name
var browserVersion = platform.version; // return browser version

```

For more examples, see platoform.js [github page](https://github.com/bestiejs/platform.js/blob/master/doc/README.md#readme)

