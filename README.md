# Functions

Functions are blocks of code that can do a task as many times as you ask it to. They take an input and return an output.

Here's a function that doubles a number:

```javascript
function double(number) {
  return number * 2;
}
```

To use the function we need to: a\) _call_ it with an input and b\) assign the returned value to a variable

```javascript
var result = double(2);

console.log(result); // 4
```

### Exercise

* Complete the function in exercise.js so that it halves the input
* Try calling the function more than once with some different numbers

> Remember to use the return keyword to get a value out of the function

### Expected result

```text
6
```

### Exercise 2

* Complete the function in exercise2.js so that it triples the input

### Expected result

```text
24
```

{% exercise %}
Define a variable `x` equal to 10.

{% initial %}
var x =

{% solution %}
var x = 10;

{% validation %}
assert(x == 10);

{% context %}
// This is context code available everywhere
// The user will be able to evaluate `exposedVar`
var exposedVar = 3;
// ... or call `exposedFunction`
function exposedFunction {
    return 3;
}
{% endexercise %}
