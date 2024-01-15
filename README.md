# Javascript function challenge
##### Function is the most beautiful part of any programming language . 
**If we perceive how function basically work in javascript** ,
We can do so many beautiful thing, write clean code and solve any coding problem by using Function  . 


# Create Javascript One-Liners by using function :
In Javascript function is a powerful that can do a lot with very little code.

#### Before take this challenge we must contain clear about 
- ES6
- array method
- string method
- number method
- pure and higher order function of javascript
###### But If you are beginner then no problem, In solution part I explain everything
  
### So here we start our exciting JS function challenge... 

### How to Capitalize Text 
- The function will capitalize the first word any text .

```js
const name = "shamin"
capitalize(name) // "Shamim"

```

 We can make a capitalize function which accepts some text. Makes the first letter uppercase and return it, then appends the rest of the string.

 ## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const capitalize = (str) => (`${str.charAt(0).toUpperCase()}${str.slice(1)}`)

```
### Explanation
- Template literals are literals delimited with backtick ( ` ) characters, allowing for multi-line strings, string interpolation with embedded expressions, and special constructs called tagged templates.
- The charAt() method returns the character at a specified index (position) in a string.
  ```js
  let name = "yusuf";
  console.log(text.charAt(0)); // "y"
  console.log(name.charAt(2)); // "s"
  ```
- The slice() method of Array instances returns a shallow copy of a portion of an array into a new array object selected from start to end ( end not included) where start and end represent the index of items in that array. The original array will not be modified.
```js
// in array
const cities = ["Feni", "Dhaka", "Shirajgong", "Noakhali", "Dinajpur"];
console.log(cities.slice(2, -1)) ; // ["Shirajgong", "Noakhali"]
// in string
const name = "My name is Yusuf Shahin";
console.log(name.slice(3, -6)) // "name is Yusuf "

</details>

### 2. How to Calculate Percent
- This function take two number as input and return the parcentage of those number.  

```js
const rightAnswer = 14;
const totalAnswar = 20;

calculatePercent(rightAnswer, totalAnswer); // 70%

```
Calculating a percent is pretty easy and just involves some simple math. It is an essential task if you want to display user progress, for example in incrementing a progress bar.

## Solution

<details>
  <summary>Click For Solution</summary>

```JS
const calculatePercent = (value, total) => (Math.round((value / total) * 100) + "%" );

```
### Explanation
- calculatePercent accepts a certain amount, divides it by the total amount, then multiplies it by 100.
- Math. round() is a built-in function in JavaScript that is used to round a number to the nearest whole number. Here's an example of how to use Math.round() :
```js
let a = Math.round(2.51); // 3
let b = Math.round(2.50); // 3
let c = Math.round(2.49); // 2
let d = Math.round(2.48); // 2

```
</details>


