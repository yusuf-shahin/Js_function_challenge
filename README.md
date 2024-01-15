# Javascript function challenge for beginner
##### Function is the most beautiful part of any programming language . Function work like a machine for programming language. It take some input and return a result. In beginning stage we must understand how function basically work and what can we do by using the power of function .
**If you are self-taught programmer and perceive how function basically work in javascript** ,
you can do so many beautiful thing, write clean code and solve any coding problem by using Function  .  
###### For that reason you must a challenge, solution some problem by using function...


# Create Javascript One-Liners by using function :
In Javascript function is a powerful that can do a lot with very little code.

#### Before take this challenge we must contain clear about 
- ES6
- array method
- string method
- number method
- math method
- pure and higher order function of javascript
###### In solution part I will explain everything
  
## So here we start our exciting JS function challenge... 

### 1. How to Capitalize Text 
- The function will capitalize the first word any text .

```js
const name = "shamin"
capitalize(name) // "Shamim"

```

 We can make a capitalize function which accepts some text. Makes the first letter uppercase and return it, then appends the rest of the string.

 ###### Solution

<details>
  <summary>Click For Solution & explanation</summary>

  ```JS
  const capitalize = (str) => (`${str.charAt(0).toUpperCase()}${str.slice(1)}`)

  ```
  ### Explanation
  - Template literals are literals delimited with backtick ( ` ) characters, allowing for multi-line strings, string interpolation with embedded expressions, and special constructs called tagged       templates.
  - The charAt() method returns the character at a specified index (position) in a string.
  ```js
  let name = "yusuf";
  console.log(text.charAt(0)); // "y"
  console.log(name.charAt(2)); // "s"
  ```
  - The slice() method of Array instances returns a shallow copy of a portion of an array into a new array object selected from start to end ( end not included) where start and end represent the       index of items in that array. The original array will not be modified.
  ```js
  // in array
  const cities = ["Feni", "Dhaka", "Shirajgong", "Noakhali", "Dinajpur"];
  console.log(cities.slice(2, -1)) ; // ["Shirajgong", "Noakhali"]
  // in string
  const name = "My name is Yusuf Shahin";
  console.log(name.slice(3, -6)) // "name is Yusuf "
  ```

</details>

### 2. How to Calculate Percent
- This function take two number as input and return the parcentage of those number.  

```js
const rightAnswer = 14;
const totalAnswar = 20;

calculatePercent(rightAnswer, totalAnswer); // 70%

```
Calculating a percent is pretty easy and just involves some simple math. It is an essential task if you want to display user progress, for example in incrementing a progress bar.

###### Solution

<details>
  <summary>Click For Solution & explanation</summary>

```JS
const calculatePercent = (value, total) => (Math.round((value / total) * 100) + "%" );

```
### Explanation
- calculatePercent accepts a certain amount, divides it by the total amount, then multiplies it by 100.
- Math.round() is a built-in function in JavaScript that is used to round a number to the nearest whole number. Here's an example of how to use Math.round() :
```js
let a = Math.round(2.51); // 3
let b = Math.round(2.50); // 3
let c = Math.round(2.49); // 2
let d = Math.round(2.48); // 2

```
</details>

### 3. How to Get a Random Element
- This function take a array as input and return a random index of this array

 ```js
const items = ["Sajid", "Osama", "Mohammad", "Umair"];

getRandomItem(items); // "Osama"
```
Getting a random element and array is really nice when you want to make things unique for your user.

###### Solution

<details>
  <summary>Click For Solution & explanation</summary>

```JS
onst getRandomItem = (items) =>  items[Math.floor(Math.random() * items.length)];

```
### Explanation
- item is an array and we pick an index of item
- The Math.floor() static method always rounds down and returns the largest integer less than or equal to a given number. Here's an example of how to use Math.floor() :
```js
let a = Math.round(2.81); // 2
let b = Math.round(7.33); // 7
```
- Math.random() static method returns a floating-point, pseudo-random number that's greater than or equal to 0 and less than 1, with approximately uniform distribution over that range. Here's an example of how to use Math.random() :
  ```js
  console.log(Math.random) // 0.43245663222234244
  console.log(Math.random) // 0.09876964334327787
  ```
  - length is a property of arrays in JavaScript that returns or sets the number of elements in a given array. For example
    ```js
    const product = ["table", "chair", "pen", "book"];
    console.log(product.length) // 4
    ```
</details>


 


