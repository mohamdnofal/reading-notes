# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

- Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

1 -Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.

2- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).

3- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

**INTRODUCING HTML5 STORAGE:**

- Simply HTML5 , it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

***USING HTML5 STORAGE:***

- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

***TRACKING CHANGES TO THE HTML5 STORAGE AREA:***

- If you want to keep track programmatically of when the storage area changes, you can trap the storage event.

- The storage event is supported everywhere the localStorage object is supported.
