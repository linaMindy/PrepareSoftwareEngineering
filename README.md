# PrepareSoftwareEngineering
Can create the rapid prototype via node.js for the software system
You guys can refer to the following link :https://nodejs.dev/learn 

Step1  : Install NodeJs 

//app.js  
const http = require('http');

const hostname = '127.0.0.1';
const port = 3000;

const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Hello World');
});

server.listen(port, hostname, () => {
    console.log(`Server running at http://${hostname}:${port}/`);
});



Step2: config Server of Http
