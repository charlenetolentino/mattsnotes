# State and Props

[Home](/README.md) | [Back](/301-main/301TableofContents.md)

Reading : [React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

Questions: 

  1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
      <ul>
      <li>Based on the diagram the 'render' phase comes before the 'componentDidMount</li>
      </ul>
  1. What is the very first thing to happen in the lifecycle of React?
      <ul>
      <li>The first thing to happen in the cycle of react is when the instance of the component is being created.</li>
      </ul>
  1.	Put the following things in the order that they happen: ComponentDidMount, render, constructor, componentWillUnmount, React Update.
        <ol>
          <li>constructor</li>
          <li>render</li>
          <li>ComponentDidMount</li>
          <li>React Update</li>
          <li>componentWillUnmount</li> 
          (not really that sure on the order of the last 2)
        </ol>
  1.  What does componentDidMount do?
      <ul>
        <li>The componentDidMount is used to load data using a network request. This method is a good place to add a subscription if needed.</li>
      </ul>
___
Video: [React State Vs. Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

Qusetions:
   1. What types of things can you pass in the props??
      <ul>
      <li>The variables you want your component to initialize to or what you want to render</li>
      </ul>
  1. What is the big difference between props and state?
      <ul>
      <li>Props are passed into a component for the outside whereas State is handled inside the component where it can be updated. </li>
      </ul>
  1. When do we re-render our application?
      <ul>
     <li>The section will re-render when you change the state in the application</li>
      </ul>
  1. What are some examples of things that we could store in state?
      <ul>
        <li>State is used when need to store a variable that is being updated based on user input. One example of where state can be used is the data being input a form or another is in the use of a counter where you are continually updating the state based on user input.</li>
      </ul>

## Things I want to know more about

1. I want to see more expamples of state and props
1. I don't really understand what the 'componentDidMount()' method does.
1. More calrity on how important the compnent lifecycle is. (I under stand that it is important but how much will I mess up if I don't comprehend this 100%)
