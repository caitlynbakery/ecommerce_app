# Ecommerce App

This app is a command-line app that has 3 different classes: Product, Item, and Cart.
The Product class has arguments for id, name, and price and
methods that display the name of the Product and the first letter
of the Product.

## Functional Programming Concepts

### Map

A map is a higher-order function that runs a function through every item in the list.
THe map iterates the whole list and returns new values as a list with the same length.

This is an example in javascript!

```javascript
var numbers = [3, 56, 2, 48, 5];

const newNumbers = numbers.map(function double(x) {
    return x * 2;
  });

//output: (5) [6, 112, 4, 96, 10]
```

The map function doesn't edit the original list, but returns a new list. In the example below,
I log `newEmojipedia` and not `emojipedia`.

```javascript
const newEmojipedia = emojipedia.map(function (x) {
  return x.meaning.substring(0, 100);
});

console.log(newEmojipedia);
```

### Reduce

Reduce is also a functional operator that iterates through a list and combines the values together.
The result of a reduce function is a single value whereas other functional operators such as map and filter return a list.

my example in javascript:

```javascript
var numbers = [3, 56, 2, 48, 5];

var newNumber = numbers.reduce(function (accumulator, currentNumber) {
  return accumulator + currentNumber;
});

//output: 114
```
