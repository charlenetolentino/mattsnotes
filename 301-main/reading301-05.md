# Putting it all Together

[Home](/README.md) | [Back](/301-main/301TableofContents.md)

## Reading: [React Docs](https://reactjs.org/docs/thinking-in-react.html)


Questions: 

1. What is the single responsibility principle and how does it apply to components?

    <ul>
      <li> A concept should ideally do just one thing. If you need it to do more then it should be split in smaller sub-components</li>
    </ul>
      
1. What does it mean to build a ‘static’ version of your application?


    <ul>
      <li> A version of your app that doesn't have a lot of moving parts. No state is used at all in a static app since state is  used to interact with the page. </li>
    </ul>

1. Once you have a static application, what do you need to add?


    <ul>
      <li>You will need to add state</li>
    </ul>

1. What are the three questions you can ask to determine if something is state?


    <ul>
      <li> 1. Is it passed from a parent through props? if yes it is not state. 2. Does it change? if yes then it is likely state. 3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
 </li>
    </ul>

5. How can you identify where state needs to live?


    <ul>
      <li> Identify if something is state. If a component shares a Parent with an other then the state should be kept with in with that common Parent.</li>
    </ul>
___

## Reading: [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

Questions: 

Questions: 

1. What is a “higher-order function”?

    <ul>
      <li> Its a function that uses other functions as arguments </li>
    </ul>
1. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

    <ul>
      <li> The variable m is set to return if m is greater than n</li>
    </ul>

1. Explain how either map or reduce operates, with regards to higher-order functions.

    <ul>
      <li> The map method transforms an array by applying a function to all of its elements and is pushed into a new array of those new values. </li>
    </ul>


____
## Things I want to learn more about

1. I want to see more uses of Higher-Order Functions
