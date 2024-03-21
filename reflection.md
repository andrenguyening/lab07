# Understanding Web Servers and Flask

## What is a web server related to Flask?

A web server in the context of Flask is responsible for handling HTTP requests and serving HTTP responses. In the Flask framework, the built-in development server provided by Flask itself handles this task during development. However, in production environments, more robust web servers like Nginx or Apache are typically used to serve Flask applications.

## How do users access resources from a web server?

Users access resources from a web server by making HTTP requests. These requests can be of various types, such as GET, POST, PUT, DELETE, etc. The web server processes these requests and returns appropriate HTTP responses, which can include HTML pages, JSON data, images, files, or any other resources requested by the user.

# Understanding GET and POST Methods in HTTP

## What is GET?

GET is an HTTP method used to request data from a specified resource. When a client sends a GET request, it retrieves data from the server without modifying any resources. This method is often used for fetching data from a server, such as loading a web page or requesting information from an API.

## What is POST?

POST is an HTTP method used to submit data to be processed to a specified resource. When a client sends a POST request, it sends data to the server, which may then process that data and return a response. This method is commonly used for actions that modify server-side data, such as submitting a form or uploading a file.
