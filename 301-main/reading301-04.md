# React and Forms

[Home](/README.md) | [Back](/301-main/301TableofContents.md)
 
Reading : [Forms](https://reactjs.org/docs/forms.html)

Questions: 

1. What is a ‘Controlled Component’?

      <ul>
      <li>A Controlled Component is and input form element whose value is controlled by React </li>
      </ul>
1. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
      <ul>
      <li> Each keystroke will update the state to prevent data lost</li>
      </ul>
1. How do we target what the user is entering if we have an event handler on an input field?

      <ul>
      <li>Use the onChange = {this.handlechange} inside the form of the component </li>
      </ul>
