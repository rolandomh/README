
# 201 d66
# Read13.md
Reading notes and Repo updates from an aspiring WebDev.
[Type-copy](http://diveinto.html5doctor.com/storage.html)

### Reading13
list of links @ canvas
#### *THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS*
What we really want is a lot of storage space, on the client, that persists beyond a page refresh, and isn’t transmitted to the server.
!!! HTML5 BABY !!!
#### 
Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.
##### HTML5 STORAGE SUPPORT:
IE	FIREFOX	SAFARI	CHROME	OPERA	IPHONE	ANDROID
8.0+	3.5+	4.0+	4.0+	10.5+	2.0+	2.0+
From your JavaScript code, you’ll access HTML5 Storage through the **localStorage object** on the **global window** object. 
Before you can use it, you should detect whether the browser supports it.
### To check for HTML5 Storage:
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
**Instead of writing this function yourself, you can use Modernizr to detect support for HTML5 Storage. 

if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
to further HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:

var foo = localStorage.getItem ( "b ar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar " ] ;
// ...
localStorage["bar"] = foo;
There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
} ;
Calling removeItem() with a non-existent key will do nothing.

Finally, there is a property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).

interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index );
} ;
If you call key() with an index that is not between 0–(length -1), the function will return null.
### Limitations of the now-standardized HTML5 Storage in order of importance:
#### “5 megabytes,” 
**amount of storage**
#### “QUOTA_EXCEEDED_ERR,” 
**“QUOTA_EXCEEDED_ERR”** is the exception that will get thrown if you exceed your storage quota of 5 megabytes.
#### “no.”
**“No”** “Can I ask the user for more storage space?-no.” no current browser supports any mechanism for web developers to request more storage space.


I suggest taking a week or so and exploring the article posted above with pertinent info.


### Article: “6 Reasons for Pair Programming”
1. so you have extra eyes.
2. so you have extra hands.
3. so you have extra brains.
4. so theres a higher statistical chance you'll have some "sense" between the two assumed huemans. 
5. see reason 6.
6. see reason 1. (this is a loop and call back.HOLLAH!)
