# Authentication
[Home](/README.md) | [Back](/401-main/401TableofContents.md)


Questions: 

1. Explain what a “Singleton” is (in Computer Science terms)

- its a design pattern that restricts the instants of a class to a single instance. 

2. Explain how the Singleton pattern can be used with Node modules, specifically with classes

- A singleton pattern is used to get and instance of a node

3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

- The middleware that I created will have to be on it own file. After exporting the middleware file I will require it in the server.js using app.use. In the previous labs we used the logger and validator as bild yo own middleware.

Vocab:


Router Middleware - middlware used in within the router

Dynamic Module Loading - a tool used by a computer program that load a library into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory. [Wiki](https://en.wikipedia.org/wiki/Dynamic_loading)

Singleton Pattern - a software design pattern that restricts the instantiation of a class to one "single" instance

CRUD -> REST methods

    Create = POST
    Read = GET
    Update = PUT or PATCH
    Delete = DELETE


Mock Testing - a testing enviorment using fake or mock data to run tests

Which 3 things had you heard about previously and now have better clarity on?

- Honestly, a little bit of everything

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?

- My testing isn't doing what I want it to, so that mainly.

What are you most excited about trying to implement or see how it works?

 - auth I guess


Readings for later:

- [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

- [bcrypt docs](https://www.npmjs.com/package/bcrypt)
