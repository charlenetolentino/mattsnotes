# Reading 9 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)

## Forms

Forms are a printed document that contains spaces for you to fill in information. The website Google is an example of a form. There are several types of form controls. You can add text via a text input, password input and text area, making a choice using radio buttons, check boxes and dropdown boxes, there are submitting forms to submit data and finally a way to upload files. \<form> is the element tagged used. Inside there are also should be an \<action> element, a method either get or post, and usually and id attribute or type. Forms are great ways to collect information for a visitor. HTML5makes form validation and data input much easier for the user experience. 

Here is an example of a text area box:

    <form action="https;//www.salmoncookies.com/comment.php">
      <p> Please leave any feedback you have for our store </p>
      <textarea name ="comments" cols="20" rows="4"> Enter your comments here </textarea>
    </form>

This example is creating a form for a comment section of a webpage called Salmon Cookies. This is an area where customers can leave feedback to the owner of the site. The active element is the URL of the page. Inside the \<p> element is the main text instruction what the customer should do if they want to leave a comment. Inside the \<textarea> tags are the detentions that the text box will be upon load as well as how many rows.   

___
## CSS Lists, Tables, and Forms


There are several CSS properties that are specifically used to work HTML elements such as list tables and form. You can control the type of bullet point used for an unordered or ordered list as well as show or take away stylings for empty cells in a table. For forms field sets are used to determine the edges of a form helping them group together related information within. Forms specifically benefit more from styles that are more interactive and are easier to use if the controls for the form are vertically aligned. Depending on the web browser forms will look slightly different.
