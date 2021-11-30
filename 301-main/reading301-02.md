# State and Props

[Home](/README.md) | [Back](/301-main/301TableofContents.md)

[React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

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


