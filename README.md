##depends on
node.js@0.8.21  
socket.io@0.9.11

##How to run

* run command

node socket_io_server.js 20082

* then run from other terminal

node socket_io_server.js 20083

* then access
http://localhost:20082/logger_socket_io  
http://localhost:20083/logger_socket_io


* then run from other terminal

node emit.js
	

* then access
http://localhost:20082/logger_socket_io  
http://localhost:20083/logger_socket_io

***

* compare

↓

io.namespaces[''].sockets[socket.id] is still them.