# Reading 4 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)

## HTML Links

  Links are used to move you from one page to another, a different section of the same page, to another website, to a new browsers window, or to open your email app to send an email to someone. In each of the cases you will use the \<a href=””>\</a> tag. Below are these examples:

  

### <b>Linking to a new website</b>

  To link to a new website, you will need the Uniform Resource Location or the URL for short. 

    <a href="https://github.com/">GitHub Homepage</a>

Notice after the URL the name of the link will be before the \</a> tag

### <b>Linking to a diffrent page on the website </b>

  Though you can use the URL for a different page on the website, but it is faster to use the relative URL such as index.HTML, about-us.HTML or contact.HTML. NOTE that there are files in the same directory

    <a href="index.HTML"> Homepage</a>
    <a href="index.about-us"> About Us</a>
    <a href="index.contact"> Contact Page</a>

### <b> Linking to Another Diffrent Part on the Same Page </b>

  For this you will need to assign and id attribute to the element. By assigning the element you are able to add the id in the href space. 

    <h1 id="Top">Top<a>
    <a href="#Top">Top</a>

### <b> Linking to Open a new Window </b>

  For this in the \<a> tag you will need to add a target=”_blank” after the URL

    <a href="https://github.com/" target="blank">GitHub Homepage</a>

### <b> Email Link </b>

  To link an email you will need to preface the email address with "mailto:”

    <a href="mailto:example@gmail.com/">Example email link</a>
___
## Layout

  As previously noted, CSS treats each HTML element as if it were in a box. These boxes will either be a block-level or and inline box. A block-level element would be tag such as \<h1>\<p> and \<ul> where an inline element would be \<img>\<b> and \<i>. Using these box types we are able to move or position these boxes in different ways following positions schemes.

### Normal Flow

  All block-level elements are on their own line lower than the previous box. This is the default position. 
    
    h1 {
      position:static;
    }

### Relevant Postion

  This moves the position to the same position as the normal flow but shifting it to the right, left, up or down. This does not affect the placement of the other boxes and the position cam be denoted by a percentage or pixel count.

    h1 {
      position:relative;
      top: 5px;
      right: 50%;
    }

### Absoulte Positioning

  Absolute position the element by taking it out of the normal flow and ignores the space around it sometimes over other boxes. Note a Width must be set.

     h1 {
      position:absolute;
      top: 5px;
      right: 50%;
      widith :250px;
    }

### Fixed Positioning

  Fixed positioning is a type of absolute positioning but is specific to a browsers window. Elements in the positioning do not affect elements around them.

     h1 {
      position:fixed;
      top: 5px;
      right: 50%;
      widith :250px;
      margin: 0px;
      background-color:yellow;
    }

### Float

  Float can be used in different ways. In its base form if you float an element to on direction, right or left, the other elements will flow around the floated element. You must set a width to the floated box so the other elements can know where to move around. 

    h1 {
      float: left;
      top: 5px;
      right: 50%;
      widith :250px;
      margin: 0px;
      background-color:yellow;
    }

Float can also be used to create column on the page as opposed to the default list. 

    .column1of3, .column2of3, .column3of3{
      width: 150px;
      margin: 10;
    }

___
 ## Functions

  
Functions allow you to group a series of statements together to do a specific task. In doing this, the overall script will run faster due the lines of code being able run at specific time rather than them running all concurrently after one another. This can reduce the possibility of repeat code and make it a lot easier to read for the future. 

Here is an example of a function

    function validateUserPassword() {
    var storedPassword = "Yo";
    var userPassword =  "";

    while(userPassword !== storedPassword) {
        userPassword= prompt('Type "Yo"');
    }

    validateUserPassword ()


On the first line the function validateUserPassword() is declared. Inside the curly bracket are the variables that are declared as well as a while loop. When a var is declared in a function, this is called being in the local scope. Any var declared in the function will only be available to use inside unless you sure the return feature. The while loop is wanting a user input of “Yo” to break out of it. This function is not declared until the function name has been called later in the code as shown on the last line.

___
