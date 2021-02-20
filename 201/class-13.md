# Past, Present and Future of Local Storage
## Cookies
Cookies were invented early in the webs history and have a few downsides:
1. Cookies slow down your web application by needlessly transmitting the same data over and over
1. Cookies send data unencrypted over the internet, unless your entire web application is served over SSL
1. Cookies are limited to about 4 KB of data — enough to slow down your app, but not enough to be useful

## HTML5 Storage
From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. 

> It’s a way for web pages to store key/value pairs locally. Like cookies, this data persists even after you navigate away from the web site. Unlike cookies, this data is never transmitted to the remote web server. It's implemented natively in web browsers, so it is available even when third-party browser plugins are not.

##### Browser Versions that Support HTML5 Storage

IE | FireFox | Safari | Chrome | Opera | IPhone | Android
----------------------------------------------------------
8.0+ | 3.5+ | 4.0+ | 4.0+ | 10.5+ | 2.0+ | 2.0+

### Using HTML5 Storage

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. Regardless, data is stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like `parseInt()` or `parseFloat()` to change your retrieved data into the expected JavaScript datatype.

Calling `setItem()` with a named key that already exists will silently overwrite the previous value. Calling `getItem()` with a non-existent key will return null.

Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the `getItem()` and `setItem()` methods, you can simply use square brackets.

[Back to Main Page](../README.md)
