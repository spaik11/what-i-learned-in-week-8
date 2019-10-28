# What-I-Learned-In-Week-8
### For of Loop
A different way of looping. Easier to read if there are no index to count or follow.
```
const colors = ['orange', 'blue', 'red', 'green', 'yellow'];

for (const color of colors) {
    console.log(color);
}
```

---
### Functions in Functions
Functions are variables. Anonymous function does not have a function name but it's assigned to a variable.
```
function sayHi() {
    return 'hiiii';
}

const hello = sayHi
console.log(hello());
```

```
const hello = function() {
    return 'hiiii'
}
const goodbye = function() {
    return 'bye now'
}
```