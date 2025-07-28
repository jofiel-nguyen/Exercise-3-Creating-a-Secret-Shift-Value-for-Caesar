# Exercise-3-Creating-a-Secret-Shift-Value-for-Caesar
#Question 5 
```
Caesar wants to represent this shiftValue as a secret emblem. If the shiftValue is, for example, 15, he wants to display it as "The emblem reveals a shift of 15 positions." Write a piece of code that constructs this string using the shiftValue variable.

Answer 

JavaScript

const randomDecimal = Math.random();
const range = 33 - 3 + 1;
const randomInRange = randomDecimal * range;
const randomInt = Math.floor(randomInRange);
const shiftValue = randomInt + 3;

const emblemMessage = `The emblem reveals a shift of ${shiftValue} positions.`;
console.log(emblemMessage); // Example Output: The emblem reveals a shift of 15 positions.
```
