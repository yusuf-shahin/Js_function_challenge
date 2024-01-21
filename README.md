# 🥇 Javascript function challenge for beginner 🥇
##### Function is the most beautiful part of any programming language . Function work like a machine for programming language. It take some input and return a result. In beginning stage we must understand how function basically work and what can we do by using the power of function .
**If you are self-taught programmer and perceive how function basically work in javascript** ,
you can do so many beautiful thing, write clean code and solve any coding problem by using Function  .  
###### For that reason you must take a challenge and solve some problem by using function. 
#### For practicing purpose, I will suggest replit . Write your code in [here](https://replit.com/~)




  
## So here we start our exciting JS function challenge 🚴‍♂️

# Logic building mindset 🏗️
- First we take some very basic and beginner level logic building challeng by using javascript function 🚶
  

### 1. Find the largest number in an array 
- This function take a array as input then return the largest number from this array .

```js
  const numbers = [90, 44, 54, 21, 44, 87, 92, 76, 55, 76, 54, 12];

  console.log(largestNumberFunc(numbers)); // 92
```
##### Solution part
  
<details>
  <summary>Click For Solution & explanation</summary>

  ```JS
  const removeDuplicates = (arr) => [...new Set(arr)];

  ```
  ### Explanation
 
```js

```
</details>


# One Line punch 👊
- JavaScript is a powerful language that can do a lot with very little code. In some cases, the amount of code you need to write doesn't exceed more than a single line, which is why they are known as one-liners.

#### Before take this challenge we must contain clear about 
- ES6
- array method
- string method
- number method
- math method
- pure and higher order function of javascript
###### In solution part I will explain everything :basecamp:

### 1. How to Capitalize Text 
- The function will capitalize the first word any text .

```js
const name = "shamin"
capitalize(name) // "Shamim"

```

 We can make a capitalize function which accepts some text. Makes the first letter uppercase and return it, then appends the rest of the string.

 <h5 style="color:red;"> Solution part </h5>

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

<h5 style="color:red;"> Solution part </h5>

<details>
  <summary> Click For Solution & explanation</summary>

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
- This function take a array as input and return a random index of this array .

 ```js
const participator = ["Sajid", "Osama", "Mohammad", "Umair", "Nushaib", "Ittihad"];

getRandomItem(participator); // "Osama"
```
Getting a random element and array is really nice when you want to make things unique for your user.

<h5 style="color:red;"> Solution part </h5>

<details>
  <summary>Click For Solution & explanation</summary>

```JS
onst getRandomWinner = (winner) =>  winner[Math.floor(Math.random() * items.length)];

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

### 4. How to Remove Duplicate Elements
- This function take a array as input then remove all duplicate element then return it .

  ```js
  const friendList = ["Rahin", "Shafiyer", "Noah", "Akram", "Noah" , "Rahin", "Shabab", "Noah"];

  removeDuplicates(friendList); // ["Rahin", "Shafiyar", "Noah", "Akram", "Shabab"]
  ```
  Removing duplicate values in an array is an essential task in JavaScript.You might be adding one user to another user's friends list, but you don't want that user to be added or displayed twice.

  ##### Solution part
  
<details>
  <summary>Click For Solution & explanation</summary>

  ```JS
  const removeDuplicates = (arr) => [...new Set(arr)];

  ```
  ### Explanation
  - A set is a collection of items that are unique. No element can be repeated. Set in ES6 are ordered: elements of the set can be iterated in the insertion order. The set can store any type of value whether primitive or objects. Here is the example of new set method :
```js
const letters = new Set(["a","b","c","d","a","a","a","b","f"]);
console.log(letters) // set(5) {'a','b','c','d','f'}
```
- The spread operator ( ... ) helps you expand iterables into individual elements. The spread syntax serves within array literals, function calls, and initialized properties objects to spread the values of iterable objects into separate items.  Here is the example of spredoperator :
```js
const students = [{id:1, name : "Yusuf"},{id:2, name : "Rafi"},{id:3, name : "Shakhawat"}]
console.log(...students) // {id:1, name : "Yusuf"} {id:2, name : "Rafi"} {id:3, name : "Shakhawat"}
```
</details>




