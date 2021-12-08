# API's

[Home](/README.md) | [Back](/301-main/301TableofContents.md)

## Reading: [API](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

Questions: 

1. What does REST stand for?
    <ul>
      <li>Representational State Transfer</li>
    </ul>
1. REST APIs are designed around a ____.


    <ul>
      <li>around a resource like an object or data</li>
    </ul>

1. What is an identifier of a resource? Give an example.


    <ul>
      <li>An identifier is a URI that specifically defines a resource. Example: https://thisExample-here.net/Page/1 </li>
    </ul>

1. What are the most common HTTP verbs?

    <ul>
      <li>get, post,put, delete, and patch</li>
    </ul>

1. What should the URIs be based on?

    <ul>
      <li>Nouns, not verbs</li>
    </ul>

1. Give an example of a good URI.

    <ul>
      <li>https://thisExample-here.net/cart</li>
    </ul>

1. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    <ul>
      <li>Chatty means there are multiple requests form API's. This is bad because it can tie up resources</li>
    </ul>

1. What status code does a successful GET request return?

    <ul>
      <li>200 code</li>
    </ul>

1. What status code does an unsuccessful GET request return?

    <ul>
      <li>404</li>
    </ul>

1. What status code does a successful POST request return?
    <ul>
      <li>301</li>
    </ul>

1. What status code does a successful DELETE request return?

    <ul>
      <li>204</li>
    </ul>
