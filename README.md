# destructuring-declaration.js
https://mustafauzun.co/blog/a-javascript-question/

My suggested names for this thing; destructuring declaration or restruction or instructed declaration

```js
let [{} = [arr = [], arr.length = 4]] = [];
//output: arr -> [empty x 4]

let [arr2 = [], {} = [arr2.length = 4]] = [];
//output: arr2 -> [empty x 4]

let [{} = [(function(){console.log('a')})()]] = [];
//output: hello
```
