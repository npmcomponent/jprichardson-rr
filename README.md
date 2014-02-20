*This repository is a mirror of the [component](http://component.io) module [jprichardson/rr](http://github.com/jprichardson/rr). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jprichardson-rr`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
rr
==

A simple JavaScript component to iterate an array round robin.


Why?
----

Sometimes you want to loop over an array and start at the beginning again.



Install
-------

### Node.js/Browserify

    npm install --save rr


### Component

    component install jprichardson/rr


### Bower

    bower install rr


### Script

```html
<script src="/path/to/rr.js"></script>
```


Usage
-----

### rr(array, [lastIndex])


### Example

```js
var rr = require('rr')

var list = ['a', 'b', 'c']
console.log(rr(list)) //a
console.log(rr(list)) //b
console.log(rr(list)) //c
console.log(rr(list)) //a

console.log(rr(list,1)) //c
console.log(rr(list,2)) //a 
```


### splice(array, idx, len)


### spliceCurrent(array, len)



License
-------

(MIT License)

Copyright 2013, JP Richardson


