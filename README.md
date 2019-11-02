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

---
### DOM Manipulation
```
function givePurpleBorder (event) {
    event.target.style.border = '5px solid purple';
}
document.querySelector('.class').addEventListener('mouseenter', func)
```
We can add this dynamic function.

`document.querySelectorAll('element')` - will grab the NodeList which is an array like item.

---
### Notes
* `setTimeout(func, milliseconds)` - will run the function after x amount of milliseconds.
* `setInterval(func, milliseconds)` - will run the function every x amount of milliseconds.
* Parameter order matters!
* `array.forEach(function)` - The `.forEach` method will run a loop through an array and you can make it dynamic but running a function to each item.
* Array Deconstruction