#Socket.IO remaining io.namespaces.sockets.socket

##depends on
node.js@0.8.21  
socket.io@0.9.11

##How to run

* run command

node socket_io_server.js 20082

* then access  
[http://localhost:20082/logger_socket_io](http://localhost:20082/logger_socket_io "http://localhost:20082/logger_socket_io")  
echo like  
logger_socket_io_before_emit.txt  

* then run from other terminal

node emit.js
	

* then access  
[http://localhost:20082/logger_socket_io](http://localhost:20082/logger_socket_io "http://localhost:20082/logger_socket_io")  
echo like  
logger_socket_io.txt  

***

* compare

↓

io.namespaces[''].sockets[socket.id] is still them.