# Express REST API
[Home](/README.md) | [Back](/401-main/401TableofContents.md)

Questions:

1. Name 3 real world use cases where you’d want to change the request with custom middleware
- Logging, Auth, Routing?
2. True or false: The route handler is middleware?

- true
3. In what ways can a middleware function end the process and send data to the browser?
- what is next(), Alex. (RIP)
4. At what point in the request lifecycle can you “inject” middleware?
- after request but before resopnse 
5. What can cause express to error with “Request headers sent twice, cannot start a second response”
- when you return a res.send

Vocab:

Middleware : communication code for data management 

Request Object: and http request given in object form

Response Object: the response given tot he user after making a request

Application Middleware

Routing Middleware

Test Driven Development: TDD the practice of writeing test first before actual code. 

Behavioral Testing: testing how the app reacts to the user
