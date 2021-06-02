# Reading 12 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)

## Charts

Charts are a good way to show data in a meaningful way and are more visually appealing than tables. Using a combination of HTML and JavaScript, you can make a line chart, pie chart, and a bar chart on the rendered page. 


The \<canvas> tag will have and id attribute as well as a set width and height. The ID attribute is the way into the DOM from the JS. 

The tag will look like this:

    <canvas id="cookie-sales" width="600" height="400"></canvas>

Inside the JS you will be creating data and one way to do so is by making an Object. Depending what chart you want to create the data needed will look different. 

Reference this link to learn the diffrence : [Reading 12 Chart Article](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

___

## The \<canvas> Element

### Basics
<ul>
  <li>Supplying an ID to a canvas element is a good practice</li>
  <li>Canvas can be styled like a normal image with a margin, border, etc.</li>
  <li>You can provide a tittle to a canvas tag</li>
  <li>Not all web browsers support canvas</li>
  <li>You will need backup like a static image for when a browser does not support</li>
</ul>

### Drawing with \<canvas>

<ul>
  <li>Canvas only supports 2 shapes: a rectangle and a list of points connected by lines</li>
  <li>All other shapes are created by combining paths</li>
  <li>moveTo() is a function that is very useful that is described as lifting the pen form one spot to another</li>
  <li>Use the lineTo() method to draw straight lines</li>
  <li>lineTo() takes in 2 arguments, x and y which is the destination you want the pen to draw to</li>
  <li>To draw arcs or circles use the arc() or arcTo() method</li>
  <li>Bezier and quadratic curves – bezierCurve() andquadraticCurveTo()</li>
</ul>

NOTE there are more methods to darw shape using canvas but for the intrest of time I will leave a link for the article here:
[Drawing Shapes in Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
 




<ul>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  
</ul><ul>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
</ul>
