# Programming Foundations Lesson 2.3: Objects

## Exercise 1

Given the object: 
```js
let myTV = { make: "Toshiba", model: "42XV555", resolution: "1080p" };
```
a) Using bracket notation, console log out the value of the property `resolution`.

b) Console log out a string with the values of `make` and `model` concatinated (with a space between them). Use dot-notation to retrieve the two property values.

c) Add the property `year` with the value `2008` to the Object.

d) Console log out the data type of `myTV`.

e) Declear another variable, `newTV`, of the same kind of Object, with the values `LG`, `65OLEDCX`, `2160p`, `2020`.

f) Use a `for...in` loop to list all the properties of `newTV`, on the form "value (key)".

g) Add the two TV objects to an Array named `tvs`.

h) Use a `for...of` loop to list all (ie. both) Objects in the `tvs` Array, on the form: "LG 65OLEDCX (2020), 2160p".

## Exercise 2 - Level 2

a) Add two more TVs to the `tvs` Array from Exercise 1, with these values, using push twice: 
* `TCL`, `55DP660`, `2160p`, `2018`
* `LG`, `65UN7100`, `2160p`, `2019`

b) Use the `Array.sort()` on `tvs` and list the result, using the same way as you did in 1h). What happens?

c) Make a *compare function* that sorts `tvs` based on the `year` value, listing the newest TVs first. Now list the sorted `tvs` Array (as in 1h and 2b).