# Javascript function challenge
##### Function is the most beautiful part of any programming language . 
**If we perceive how function basically work in javascript**
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

<h3> How to Capitalize Text </h3>  
- The function will capitalize the first word any text .

```js
const name = "shamin"
capitalize(name) // "Shamim"

```

 We can make a capitalize function which accepts some text. Makes the first letter uppercase and return it, then appends the rest of the string.

 ## Solutions

<details>
  <summary>Click For Solution</summary>

```JS
const capitalize = (str) => (`${str.charAt(0).toUpperCase()}${str.slice(1)}`)

```
### Explanation
- Template literals are literals delimited with backtick ( ` ) characters, allowing for multi-line strings, string interpolation with embedded expressions, and special constructs called tagged templates.
- The charAt() method returns the character at a specified index (position) in a string.
- The slice() method of Array instances returns a shallow copy of a portion of an array into a new array object selected from start to end ( end not included) where start and end represent the index of items in that array. The original array will not be modified. 


</details>

