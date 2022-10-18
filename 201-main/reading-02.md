# Reading 2 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)

## 2 Types of HTML Markup

1. Structural Markup -
    Elements like \<h1>, \<p>, \<b>, and \<i> are used in HTML are used to describe a heading or a paragraph and provide spaces for grouped up texts

1. Semantic Markup -
    These mark ups provide extra information like where to put emphasis on a word in a sentence. Elements like \<strong> \<em> and \<blockquote> just to name a few

Note that all HTML will use roughly the same structal mark ups but will uses semantic mark ups in specific areas where it is intended. 

## Using CSS

 CSS stands for **C**ascading **S**tyle **S**heets. It is used to style the webpage from top down, or in a cascading function. Meaning when  you have two of the same property with different values the web page will load the latest one. 

 For example

    p {
        color:red;
        backgroundcolor:blue;
        color:yellow;
        backgroundcolor:black;
    }
Here you see that the first text color is declared as red, and the background color is blue for the p or paragraph element. Following we see that new values, yellow and black, are declared immediately after. This is the cascading factor when you write CSS. 

You can enter CSS in 2 ways. Internlly in the HTML line or Externally on a seperate file.

Exteral CSS Pros:
1. No repeat code
1. Faster load time 
1. Easier to read and edit

Internal CSS Pros:
1. Better for a single web page
1. Used for specific rules on a more complex page

## Using JavaScript

Javascript, or JS, is a scripting language used to make web pages interactive and dynamic. Using a series of instructions called statements a computer can follow each instruction one by one. At the end of each statement will have a semicolon to denote when that instruction is completed.

Unlike a human’s brain, a computer needs to be told each step and each variable before it can do anything. A task like making a PB&J might seem thought and effortless but to a computer you will need to introduce it to the bread, the peanut butter, the jelly, the knife, or spoon to spread, the action of spreading, etc. 

Example

    var peanutButter;
    var knife;
    var jelly;
    var bread;

Here is Who declaring variables in JS looks like.

With the addition of data types like string, numerical, and Boolean logic you can write code to make a PB&J. Just don’t ask me how (right now). 

## Decisions and Loops

Scripts will act differently depending how the user will interact with the site. To help the user on where to go on your webpage or get the information they are looking for, you will need incorporate and decision tree or a loop depending on the need of the user. 

There are 2 componets ti a decision

1. 	The expression is evaluated and returns a value
2.	A conditional statement is made given a not expected value

Evaluating a decision usually consists of it being a true or false statement 

A condition statement is based on if/then/else. If the first condition is met, then it will execute without the running the then or else statements. If not, then the following script will run. 

Exapmle

    if (answer === 42) {
        document.write( 'That is the meaning of life!')
    } else {
        document.write( 'Sorry. Try again...')
    }

In this if else statement if the input is equal to the number 42 then the site will write the text “That is the meaning of life!”)
If that requirement is not correct, then the page will write “Sorry. Try again…”

Using different operators and statements you are able to write dynamic functions on the web.
