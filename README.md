# random-generator

# Description
The Random Number Generator is an npm package that allows you to easily generate a random number within a specified range. This package provides a simple and convenient way to generate random numbers for various use cases, such as games, simulations, or any scenario where random number generation is needed.

# Features:

Generate random numbers within a specified range
Specify the minimum and maximum bounds for the generated random number
Inclusive or exclusive range options for greater flexibility
Support for both integers and floating-point numbers
Easily integrate the random number generation functionality into your projects

# Installation

```shell
npm install random-num-generator11
```
# Import

```javascript
const getRandomNumber = require('random-num-generator11')
```

# Usage

```javascript
const min = 1;
const max = 100;
const randomNumber = getRandomNumber(min, max)
console.log(`Random number between ${min} and ${max}: ${randomNumber}`);
```

