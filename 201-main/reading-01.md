# Reading 1 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)


## Structure

One  way to think about how to structure a web page is to think of it like a newspaper (remember those?). On a newspaper there are titles, headings, and bodies of paragraphs but instead of typing up a word document and editing the font size and shape you will need to identify these different sections with HTML tags. These tags usually come in pairs showing you where that section begins and ends.  

For example:

    <h1> This is the main heading </h1>
    <p> This is where a paragraph will go </p>
    <h2> This would be a second heading <h2>

It is vital to learn all the HTML tags to know which are appropriate to use at certain times.

## Extra Markup

**ID Attribute:**

    <p id="insert text">

Used to ***uniquely*** identify that element form the others on the page

**Class Attribute:**

    <p class="insert text">

Used to identify ***several*** elements as being different 

**Block Elements:**

    <h1></h1>
    <p></p>
    <ul></ul>

These are used to crete a new line on the window

**iframes:**

    <iframe
    width = "x"
    height = "x"
    img=>

    </iframe>

This is used when you want to create a little window inside the web browser

## HTML5 Layout

In previous versions of HTML, the \<div> command was used to id related elements on the page. HTML5, the most recent version and the version that we use in class, took the most used \<div> elements and created their very own HTML tag.

**Pre-HTML5**

    <div id="header">
    <div id="nav">
    <div id="article>

**HTML5**

    <header>
    <nav>
    <article>

The use of these elements provides a cleaner code and make it easier for screen reading software to read pertinent information like the body of an article instead of information on the header and footer of the web page. In addition, these new tags can be used by search engine to provide more accurate search results 

## Process and Design 

When creating a website, it is important to design it for a target audience in mind. 
Here are a few questions you want to ask when you are at the early stages of building a website:

**Who is the site for?**

Every website has a target audience. They can be as broad as a Facebook audience where the platform must be user friendly for a variety of age, occupation, county of origin, and gender or it can be more specific like PBS Kids where their target audience is mainly kids. Once you identify who you want to use your website it will be easier to build around those needs.

**Why are people visiting your website?**

Most visitors will come to your site for a specific reason. You can determine these reasons by asking what their key motivations are and what are their specific goals.

**What information your visitor needs?**

After learning who is coming to your site and why, you need to find out what information they need to reach their goals quickly. Are these subject matter experts with tons of experience and knowledge or are they novices who need background information on a product or services that you are providing? 

___

Once you have learned all you can about the visitor you can now create a site map and the wireframes for each page. 

**SiteMap**
![Site Map Example](/site-map.jpg) 


PC: [Arts and Justice](/https://www.artsandjustice.org/graphic-design-3-project-6-app-wireframe-site-map/the-silver-lining-presentation-template-a-free-beautiful-template-for-marketer-17-638/)

A site map will help you plan the final structure of your site

**Wireframe**
![Wireframe Example](/wireframe.PNG)


PC: [Diagram.io](https://app.diagrams.net/#G1_A_OEkC0MvwZf20gOn-W-YlYjL6HkmhV)

A wireframe will help you creat  the layout of every web page.

## What is a Script? ##

A script is a series of instructions that a computer needs to achieve a goal. Think of it like a recipe or a manual. You need to complete each step-in order to achieve and result. One key difference between how a computer reads a set of instructions and how a human reads a set is that a computer needs to complete steps programmatically. A task such as cooking lunch needs to be broken down to a computer step by step. An example would be a human will be tasked to make a PB&J sandwich. Without even thinking the human will get some bread and slather the peanut butter and jelly on and complete the task. Making a PB&J is familiar to the human, so it seems like an effortless task. A computer needs to be told “go get the bread. Go get the peanut butter. Go get the Jam. Grab the knife” etc. A great way to writing script is using a flowchart to break down the process you want to achieve.

## How to write Script? ##

JavaScript is written by creating a JS file in you text editor using the app.js extension. You will need to link the app.js extension to your HTML using the \<script> element. 
