# Read 13 Notes: Local Storage

Link: [The Past, Present, and Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)

Reference Codes: 

```
var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
```

Can be rewritten using square bracket:
```
var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;
```

Clear Entire Storage Area:

```
interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};
```

Get Total number of values in storage area
```
interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};
```

Tracking Changes: 

```
if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};
```

<br>
<br>

[Back to Table of Contents](https://davees987.github.io/reading-notes)



