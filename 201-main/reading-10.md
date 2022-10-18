# Reading 10 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)

## Debugging JS

Errors are common and it takes time to learn how to read then and Who errors to look for. To find the source of an error one must first understand the order of execution. Who functions are being called, in Who order it is being called, and Who variables it needs. Notes that some tasks cannot run without others first being declared or invoked. To better understand this execution context but be understood as well. This is where the variable scope is either global or function level. If a variable is declared by the former, then it can be used anywhere on the JS page. If it is declared by the ladder, then it can ONLY be used inside that function. 

One way you can start to debug the code is to look at the developer tools in on the web browser. Note that each web browser will have varying error messages and developers’ tools, so it is best to get familiar with the one you use the most. By starting at the developers’ tools or console, you can identify where the error occurred. Using the error information given in the browsers console, you can now look at the JS code and begin to examine specifics on the line mentioned in the error message. From here you start to debug by then figuring out Who code is working, where it its breaking, and why it broke in the first place. This is a practice that will get better the more you debug your own code and others. 

Here are a few Debugging tips:

<ul>
      <li> Remove or comment out code one line a time to see where the error is </li>
      <li> Use a search engine to find others who might of come across the same issue</li>
      <li> Try another web browser </li>
      <li> Use validation tools like jslint</li>
      <li> Get a second pair of eyes and explae to them how the code is suppose to work.</li>
      <li> Use code playgrounds like repl.it</li>
    
</ul>

