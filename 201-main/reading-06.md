# Reading 6 Notes

[Home](/README.md) | [Back](/201-main/201TableofContents.md)


## The Problem Domain

In the article, the author talks about what a problem domain is and why it is important. To program something initially, you need to know what problem you are trying to solve or what questions must be asked. Specifics must be talked about between collaborating team members. “It is very difficult to solve a problem before you know the question” writes the author. If a problem domain is too difficult it is ok to make it easier and narrowing a specific part of the problem. Reading this has opened my mind into more what it like to be a Software Developer. This is the human aspect of programming that I didn’t know was there and am happy to learn about it. 
___
## Objects

An object is a set of variables and functions grouped together to model something in the real world. A variable inside and Object is called a property. A function inside an object is a called a method. To create an object, you will first need to declare a variable and have it equal curly brackets. Then inside the curtly is when you add the properties and methods. After creating an object then you can call a method using dot notation. The period or dot is known as the member operator. 

Here is an example of creating an object and accessing a property.

    var cars = {
      name: 'toyota'
      inventory: 30
      price: 25000
      colors: ['red', 'blue', 'silver'] 

      checkInventory; function() {
        return this.invnetory - this.price;
      }

    }

    var redCar = cars.color[i]

___

## Document Object Model

<ul>
      <li> Document Oject Model (DOM) tells the browser how they will make a model of the HTML page. </li>
      <li>  You can select the element nodes by CSS ID seclector, Class selector or HTML tag to name a few.  </li>
      <li> When a Method can return more than one element it will return as a list even if it is the only one. The node list will be given index places and will be refered as a collection </li>
      <li> You can traverse through the DOM using relationship properties like parentNode, previousSibling, and lastChild to name a few.</li>
      <li>Web browsers process the DOM differently </li>
      <li>You are able to access and update text using innerHTML </li>
    </ul>


