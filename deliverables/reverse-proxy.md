Nginx  sits in front of the flask application. It receives incoming HTTP requests on port 80 or forwards it to the internal flask server.

## Benefits:
1. It acts as a buffer and prevents direct exposure of the application server to the internet.
2. It allows the application to run on a high numbered port internally while presenting a standard port 80.
