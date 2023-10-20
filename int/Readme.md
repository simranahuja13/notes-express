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
Ans. ```npm stands for Node Package Manager. It's a library and registry for JavaScript software packages.  ```

10. What is the difference between a GET and a POST request ?
Ans. ```A GET request retrieves data from a server, whereas a POST sends data to a server. With a GET request, parameters get passed in the URL. With a POST request, parameters get passed in the request's body.```
````
