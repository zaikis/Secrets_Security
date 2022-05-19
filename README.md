# Secrets_Security!



![Screenshot 2022-05-17 at 20 51 37](https://user-images.githubusercontent.com/62755319/169333403-3a0e9bf2-ca08-4559-804f-3e138183e026.png)

![Screenshot 2022-05-17 at 20 50 46](https://user-images.githubusercontent.com/62755319/169333431-4a450778-b3fa-4e64-855b-e0270fe046a3.png)
body-parser
NPM Version NPM Downloads Build Status Test Coverage

Node.js body parsing middleware.

Parse incoming request bodies in a middleware before your handlers, available under the req.body property.

Note As req.body's shape is based on user-controlled input, all properties and values in this object are untrusted and should be validated before trusting. For example, req.body.foo.toString() may fail in multiple ways, for example the foo property may not be there or may not be a string, and toString may not be a function and instead a string or other user input.

Learn about the anatomy of an HTTP transaction in Node.js.

This does not handle multipart bodies, due to their complex and typically large nature. For multipart bodies, you may be interested in the following modules:

busboy and connect-busboy
multiparty and connect-multiparty
formidable
multer
This module provides the following parsers:

JSON body parser
Raw body parser
Text body parser
URL-encoded form body parser
Other body parsers you might be interested in:

body
co-body
Installation
$ npm install body-parser
