# Reading 3 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)


## Lists in HTML

There are a few kinds of lists in HTML. Ordered, unordered and definition lists. Each having their own purposes. 

The ordered list can list out instructions in a recipe.

HTML Example:

    <ol>
      <li> Fold in egg whites </li>
      <li> Sift in Flour </li>
      <li> Gently mix in eggs yolks </li>
    </ol>

<ol>
      <li> Fold in egg whites </li>
      <li> Sift in Flour </li>
      <li> Gently mix in eggs yolks </li>
    </ol>

The unordered list can list out a grocery list.

HTML Example:

      <ul>
        <li> Eggs </li>
        <li> Flour </li>
        <li> Milk </li>
      </ul>

<ul>
      <li> Eggs </li>
      <li> Flour </li>
      <li> Milk </li>
    </ul>


Finally, the definition list can set terms with its own definition.

HTML Example: 

    <dl>
      <dt>Pokemon</dt>
      <dd> a series of Japanese video games and related media featuring cartoon monsters that are captured by players and trained to battle each other.</dd>
<dl>
      <dt>Pokemon</dt>
      <dd> a series of Japanese video games and related media featuring cartoon monsters that are captured by players and trained to battle each other.</dd>

 _____

## CSS Boxes

In CSS the HTML elements are treated as its very own box. To those boxes can control the dimensions, create styles borders around them, set the margin and the padding space between and also show a hide them. 

A couple things to keep in mind when styling your boxes:

<ol>
  <li> When choosing to dimension you can give those values using a pixel count, percentages, or em. 
  <li> Make sure to add a minimum and maximum width so that the text does not looks so wide on the screen
  <li> Adding border margin and padding can be very helpful in creating white space on the webpage
  <li>Setting parent margins left and right to auto will center give equal space to text on each side of the box
  <li> Don’t be afraid to style the border using images, box shadows, and rounded corners 
</ol>

___

## Decisions and Loops

Using Boolean true or false you are able, in a sense, have a computer decide with the use of logical operators. By comparing a given variable to a numerical value, a statement can be determined by the user input and outputted to the screen. 

Example:

    var score = promt('Hello! Guess a number between 1 and 100')
    if (score >=50 ){
      congrats();
    }
    else {
      tryAgain();
    }

In this code you the var score is declared with the prompt “Hello! Guess a number between 1 and 100”. In the if statement and the score is greater than or equal to the prompt congrats will come on the screen. If the score is less than 49 then the browser will show the tryAgain prompt.

 <i> NOTE: There are a few statements, called fasly, that do not allow and code to run. There are only a few of these since most statments are truthy but keep an eye out for zeros, empty stings, and Nan just to name a couple. </i>

Loops can also run using the keyward for,while and do while. These are usually used in an array.

Example:

    
    for ( var = 0; i < 10; i++>){
      console.log(i)
    }
In this example, from the JS Duckket book, the var i is declared in the for loop. The condition is i<10 and finally I will increment using the increment operator ++. This line of code will run as long as i remains less than 10. Once the statement returns as false, it will stop. All of this will be written in the console log.
