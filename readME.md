#Intro to HTML5 WebSockets
###Client to WebSocketServer
You don't need to start the server. Just open your index.html file in the browser. The app.js contains the web socket connection. The web socket server is an echo server so it will send back what ever message you input. 

###Server to WebSocketServer
Run your server file and it will begin to output the roundtrip time it takes for it to send a timestamp to the server and receive a message in response. The server will continue to send a timestamp every second for 10 seconds after which it will close the connection to the websocket server which will cause an error due to the program attempting to send another message to a closed connection. 
