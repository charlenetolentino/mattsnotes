# Class 1  Notes

[Home](/README.md) | [Back](/102-main/102TableofContents.md)


## Structure

One way to think about how to structure a web page is to think of it like a newspaper (remember those?). On a newspaper there are titles, headings, and bodies of paragraphs but instead of typing up a word document and editing the font size and shape you will need to identify these different sections with HTML tags. These tags usually come in pairs showing you where that section begins and ends.  

For expample:

    <h1> This is the main heading </h1>
    <p> This is where a paragraph will go </p>
    <h2> This would be a second heading <h2>

It is vital to learn all the HTML tags to know which are appropriate to use at certain times.

## Extra Markup

**ID Attribute:**

    <p id="insert text">

Used to ***uniquely*** identify that element form the others on the page

**Class Attrubute:**

    <p class="insert text">

Used to identify ***several*** elements as being different 

***Block Elements:***

    <h1></h1>
    <p></p>
    <ul></ul>

These are used to crete a new line on the window

***iframes:***

    <iframe
    width = "x"
    height = "x"
    img=>

    </iframe>

This is used when you want to create a little window inside the web browser

## HTML5 Layout

In previous versions of HTML, the \<div> command was used to id related elements on the page. HTML5, the most recent version and the version that we use in class, too the most used \<div> elements and created their very own HTML tag.

***Pre-HTML5***

    <div id="header">
    <div id="nav">
    <div id="article>

***HTML5***

    <header>
    <nav>
    <article>

The use of these elements provides a cleaner code and make it easier for screen reading software to read pertinent information like the body of an article instead of information on the header and footer of the web page. In addition, these new tags can be used by search engine to provide more accurate search results 