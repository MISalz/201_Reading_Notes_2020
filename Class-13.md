# Class 13 Notes
## Michelle Salazar

# [Storage for the web](http://diveinto.html5doctor.com/storage.html)

**userData** allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (microsoft)

**Local Shared Objects** it allows Flash objects to store up to 100 KB of data per domain (adobe)

**Gears** an open source browser plugin aimed at providing additional capabilities in browsers(google)
-Gears provides an API to an embedded SQL database based on SQLite


HTML5 Storage ( “Local Storage” or “DOM Storage.” ) it’s a way for web pages to store named key/value pairs locally, within the client web browser


JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object.

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

***data is actually store as a string***

need to use functions like parseInt() or parseFloat() 

Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.

Like other JavaScript objects, you can treat the localStorage object as an associative array.

Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:

var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage\["bar"];
// ...
localStorage\["bar"] = foo;

STORAGE EVENT OBJECT
|PROPERTY	|TYPE	|DESCRIPTION|
---|---|---
key	| string	the named key that was added, removed, or modified
|oldValue	|any	|the previous value (now overwritten), or null if a new item was added
|newValue	|any	|the new value, or null if an item was removed
|url*	|string	|the page which called a method that triggered this change

# [Home](https://misalz.github.io/Reading-Notes)
