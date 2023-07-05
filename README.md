                        ECDSA NODE 
This is my first blockchain project from Alchemy University. It is an example of a client and server to facilitate transfers between addresses. By using Elliptic Curve Digital Signatures Algorithm(ECDSA) we can make it so the server only allows transfers that have been signed for by the person who owns the associated address.

                                CLIENT


The client folder contains a react app using vite. To get started, follow these steps:

Open up a terminal in the /client folder
Run npm install to install all the depedencies
Run npm run dev to start the application
Now you should be able to visit the app at http://127.0.0.1:5173/
                                SERVER


The server folder contains a node.js server using express. To run the server, follow these steps:

Open a terminal within the /server folder
Run npm install to install all the depedencies
Run node index to start the server
The application should connect to the default server port (3042) automatically!

Hint - Use nodemon instead of node to automatically restart the server on any changes.
