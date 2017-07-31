Super Simple Testing

Research:
const
require
add
subtract
max
npm
json
console.assert()
module.exports
module

Use mocha and chai to test recommended by Jared


1. Can describe what a test is
Using console.assert() to test both expected inputs/outputs of a function

2. Can use console.assert() to write simple tests


3. Can write a function to test another function


4. Can write a test script to test one or more functions in source code file


5. Can run tests in a console


6. Can run tests from the Terminal
node <filename>

EXAMPLE:


const add = function(a, b) {
  return a +b;
}
module.exports = add

const max = function(array) {
  return array[0]
}
module.exports = max
