1. What is Node.js ?
   Ans. `Node. js is an open-source, cross-platform JavaScript runtime environment and library for running web applications outside the client's browser.`

2. What is Express.js ?
   Ans. `It is used to build a single page, multipage, and hybrid web application.`

3. What is Mongoose ?
   Ans. `manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB. `

4. What is difference between database and client-side server ?
   Ans. i.) `Database is an organized collection of data, generally stored and accessed electronically from a computer system. `

ii.) `A server is a computer program or a device that provides functionality for other programs or devices which are called clients`

5. What is the Package json file ?
   Ans. `The package. json file contains descriptive and functional metadata about a project, such as a name, version, and dependencies. `

6. How to install, update, and delete a dependency ?
   Ans. `Run the command npm install to install all the dependencies listed in your package. json file. `

7. Basic server print ?
   Ans.

````javascript
      const express = require("express");
      const app = ecpress();
      const Port = 2000;
     app.get("/",(req,res)=>{
     res.send("Hello world")
                          })
         app.listen(Port,()=>{
    console.log(`Server is Listening on port no is ${Port}`)
})```


8. What is Middleware ?
Ans. ```Middleware is software that lies between an operating system and the applications running on it. ```

9. What is NPM ?
Ans. ```npm stands for Node Package Manager. It's a library and registry for JavaScript software packages.```

10. What is the difference between a GET and a POST request ?
Ans. ```A GET request retrieves data from a server, whereas a POST sends data to a server. With a GET request, parameters get passed in the URL. With a POST request, parameters get passed in the request's body.```
````
11. What are Promise in Node .js ?
Ans. ```A promise is basically an advancement of callbacks in NodeJS. In other words, a promise is a JavaScript object which is used to handle all the asynchronous data operations.```

12. What is the difference between Express.js and Node.js ?
Ans. (Node.js):-```Node.js is an open source and cross-platform runtime environment for executing JavaScript code outside of a browser. You need to remember that NodeJS is not a framework and it’s not a programming language.```
(Express.js):- ```Express is a small framework that sits on top of Node.js’s web server functionality to simplify its APIs and add helpful new features. ```

13. Express Js install Commnad ?
Ans . ```npm install express```

14. Mongoose Js install Commnad ?
Ans . ```npm install mongoose```

15. What is a Collection in MongoDB ?
Ans . ```A collection in MongoDB is a group of documents. If a document is the MongoDB analog of a row in a relational database, then a collection can be thought of as the analog to a table.```

16. What is the Mongo Shell ?
Ans. ```It is a JavaScript shell that allows interaction with a MongoDB instance from the command line. With that one can perform administrative functions, inspecting an instance, or exploring MongoDB. ```

17. What is a callback function in Express.js ?
Ans . ```A callback function in Express.js is a type of function that is called after a specific action has occurred. For example, a callback function handles a successful or failed database query.```

18. What is the difference between res.send() and res.json() in Express.js ?
Ans. ```res.send() is used to send a response with any type of data (string, object, buffer, etc.). While res.json() is used to send a JSON response. res.json() also sets the Content-Type header to application or JSON.```

19. What is mongodb ?
Ans. ```MongoDB is built on a scale-out architecture that has become popular with developers of all kinds for developing scalable applications with evolving data schemas.```

20. What is difference between SQL and Mongodb ?
Ans. ```SQL databases are used to store structured data while NoSQL databases like MongoDB are used to save unstructured data.```
