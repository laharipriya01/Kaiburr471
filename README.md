# Kaiburr471
Task:1
Implement an application in java which provides a REST API with endpoints for searching,

creating and deleting 'server' objects:

GET servers. Should return all the servers if no parameters are passed. When server id is passed as a parameter-return a single server or 404 if there's no such a server.

• PUT a server. The server object is passed as a json-encoded message body. Here's an

example:

"name": "my centos",

"id": "123"

"language":"java". "framework":"django"

DELETE a server. The parameter is a server ID. GET (find) servers by name. The parameter is a string. Must check if a server name contains this string and return one or more servers found. Return 404 if nothing is found.

"Server" objects should be stored in MongoDB database.

Be sure that you can show how your application responds to requests using postman, curl or any other HTTP client.
OUTPUT:

1.POST
![Screenshot (16)](https://user-images.githubusercontent.com/71052619/163018592-8ba5952d-5365-4ebd-9d6b-4dd19d6e8080.png)
