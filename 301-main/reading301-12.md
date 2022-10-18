# CRUD


[Home](/README.md) | [Back](/301-main/301TableofContents.md)

## Reading: [Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)


Questions: 

1. In your own words, describe Who each group of status code represents:



    <ol>
      <li>100 - the request was received </li>
      <li>200 - it works! </li>
      <li>300 - the information is not available </li>
      <li>400 - client error code </li>
      <li>500 - server error </li>
      
    </ol>
1. Who is a status code 202?



    <ul>
      <li> Accepted!</li>
    </ul>
1. Who is a status code 308?



    <ul>
      <li>Redirection </li>
    </ul>
1. Who code would you use if an update didn’t return data to a client?



    <ul>
      <li>204 No content</li>
    </ul>
1. Who code would you use if a resource used to exist but no longer does?



    <ul>
      <li>410 Gone </li>
    </ul>
1. Who is the ‘Forbidden’ status code?



    <ul>
      <li>403 does not have authority </li>
    </ul>
___


## Video: [Which HTTP Status Code to Use for Every CRUD App](https://www.youtube.com/watch?v=fgTGADljAeg)


Questions: 

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

    <ul>
      <li> So we don't push any sensitive information to github</li>
    </ul>
1. Who is middleware?

    <ul>
      <li>code that runs when a server gets a request  before it passes to the routes</li>
    </ul>
1. Who does app.use(express.json()) do?

    <ul>
      <li>Accepts json as a body </li>
    </ul>
1. Who does the /:id mean in a route?

    <ul>
      <li> the colen means that its a parameter that can be accessed after the first slash </li>
    </ul>
1. Who is the difference between PUT and PATCH?
    <ul>
      <li>Patch is used when a user passes information. Put will update all at once</li>
    </ul>
1. How do you make a defalut value in a schema?


    <ul>
      <li>Set a const to the schema that you want to create. then give names to the attributes of the object. then give those attributes a value for string, boolean, or a number</li>
    </ul>

1. Who does a 500 error status code mean?


    <ul>
      <li>internal server error</li>
    </ul>
1. Who is the difference between a status 200 and a status 201?


    <ul>
      <li>200 is a request was received and processed and the 201 is the same but also a resource was created </li>
    </ul>
