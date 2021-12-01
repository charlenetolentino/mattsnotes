# Passing Functions as Props

[Home](/README.md) | [Back](/301-main/301TableofContents.md)

Reading : [React Docs](https://reactjs.org/docs/lists-and-keys.html)

Questions: 

  1. What does .map() return?
      <ul>
      <li> .map() returns the double values of the numbers that are input via an array</li>
      </ul>
  1. If I want to loop through an array and display each value in JSX, how do I do that in React?
      <ul>
       <li>Loops are made using curly braces for React but must also have a returned list element</li>
      </ul>
  1. Each list item needs a unique ____.
      <ul>
        <li>A unique Key </li>
      </ul>
  1. What is the purpose of a key?
      <ul>
       <li>A Key is a special attribute that needs to be included when creating lists. They help React identify which items have changed</li>
      </ul>
___

Reading : [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

Questions: 

<ol> 
  1. What is the spread operator?

      
  The spread operator is a "spread syntax" notated by three dots (...) to expand an object into their own list of arguments


  2. List 4 things that the spread operator can do.

      <ol>
       <li>Adding State to React</li>
       <li>Using and array as arguments</li>
       <li>Combining objects</li>
       <li>Using Math functions</li>
      </ol>
  1. Give an example of using the spread operator to combine two arrays.

      <ul>
        <li>A unique Key </li>
      </ul>
  1. Give an example of using the spread operator to add a new item to an array.

    const color = ['red','blue','white']
    const moreColor = [...color];
    console.log(moreColor) // Array(3) [ "red", "blue", "white",]
    color[0] = 'pink'
    console.log(...[...color,'...',...color]) //  pink blue white ... red blue white

  5. Give an example of using the spread operator to combine two objects into one.

    const array1 = ['red','blue','white']
    const array2 = ['pink', 'green', 'purple']
    const array3 = [...array1,...array2]
    console.log(...array3) // red blue white pink green purple

</ol>

___

Video: 
