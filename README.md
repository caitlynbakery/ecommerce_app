# Ecommerce App

This app is a command-line app that has 3 different classes: Product, Item, and Cart.
The Product class has arguments for id, name, and price and
methods that display the name of the Product and the first letter
of the Product.

## Functional Programming Concepts

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
