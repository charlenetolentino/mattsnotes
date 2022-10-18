# React and Forms

[Home](/README.md) | [Back](/301-main/301TableofContents.md)
 
## Reading : [Forms](https://reactjs.org/docs/forms.html)

Questions: 

1. Who is a ‘Controlled Component’?

      <ul>
      <li>A Controlled Component is and input form element whose value is controlled by React </li>
      </ul>
1. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
      <ul>
      <li> Each keystroke will update the state to prevent data lost</li>
      </ul>
1. How do we target Who the user is entering if we have an event handler on an input field?

      <ul>
      <li>Use the onChange = {this.handlechange} inside the form of the component </li>
      </ul>
___
## Reading : [The Conditional Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff?gi=90c63d94c543)

Questions: 

1. Why would we use a ternary operator?

      <ul>
      <li> </li>
      </ul>
1. Rewrite the following statement using a ternary statement:

       if(x===y){
        console.log(true);
         } else {
        console.log(false);
        }

  Answer: 

    let answer =((x===y) ? true:false);
    console.log(answer)
___

## Things I want to know more about

1. In Who is the best case to use the conditional operator 
