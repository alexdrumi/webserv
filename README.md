<div align="center">
   <a href="https://github.com/alexdrumi/webserv">
     <img src="data/www/webserver.jpg" alt="MNE EEG Logo" width="550" height="250">
   </a>
 </div>
 
 
 # WEBSERV
 > A lightweight, C++98-based web server, inspired by how Nginx handles basic HTTP functionality.
 
 <br>
 
 [![C/C++ CI MacOS](https://github.com/xvoorvaa/webserv/actions/workflows/macos_comp.yml/badge.svg)](https://github.com/xvoorvaa/webserv/actions/workflows/macos_comp.yml)
 [![Catch2 Unit Tester (MacOs)](https://github.com/xvoorvaa/webserv/actions/workflows/Catch2_unit_tester.yml/badge.svg)](https://github.com/xvoorvaa/webserv/actions/workflows/Catch2_unit_tester.yml)
 
 ## Table of Contents
 * [General Info](#general-information)
 * [Technologies Used](#technologies-used)
 * [Features](#features)
 * [Screenshots](#screenshots)
 * [Setup](#setup)
 * [Usage](#usage)
 * [Contact](#contact)
 
 
 ## General Information
 Webserv is a hand-crafted web server designed to mimic some of the fundamental behavior of Nginx-handling requests, serving static files, and invoking external scripts. By reimplementing these core features, we provide an immersive learning experience about:<br>
 
 - WebSockets and CGI (Common Gateway Interface).<br>
 - System-level details like sockets, blocking vs. non-blocking I/O, and poll-based concurrency.<br>
 - The HTTP protocol (headers, status codes, etc.).<br>
 - HTML5 and CSS (for basic web pages)
 
 
 ## Technologies Used
 - C++98 (core language)
 - Python3 (for CGI scripts)
 - HTML5 and CSS (for basic web pages)
 
 
 ## Features
 - HTTP requests: GET, POST, DELETE 
 - File upload via POST request
 - CGI - displaying a page via the python interpreter
 - Directory listing
 
 
 ## Screenshots
 ![Example screenshot](./data/www/screenshot.png)
 
 
 ## Setup
 Requirements are:
 - C++98
 - Python3 (/usr/local/bin/python3)
 - Mozilla Firefox
 - Config file
 
 
 ## Usage
 `make && ./webserv data/conf/default.conf`
 
 Or after make, provide your own custom .conf file.
 
 `make && ./webserv you_own_conf_file`
 
 ### Once the server is running with the default.conf config file, you can reach it at: localhost:80
 
 ## Sources
 - [What is a socket](https://beej.us/guide/bgnet/html/index-wide.html#:~:text=2-,What%20is%20a%20socket%3F,-You%20hear%20talk)
 - [Dealing With and Getting Around Blocking Sockets](http://dwise1.net/pgm/sockets/blocking.html)
 - [HTTP Made Really Easy](https://www.jmarshall.com/easy/http/)
 [Structure of HTTP transactions](https://www.jmarshall.com/easy/http/#:~:text=Table%20of%20Contents-,Structure%20of%20HTTP%20Transactions,-Like%20most%20network)
 - [Sample HTTP Exchange](https://www.jmarshall.com/easy/http/#:~:text=Table%20of%20Contents-,Sample%20HTTP%20Exchange,After%20sending%20the%20response%2C%20the%20server%20closes%20the%20socket.,-To%20familiarize%20yourself)
 - [Diagram for server](https://i.stack.imgur.com/YQ5ES.png)
 - [Lecture that explains sockets pretty well with examples (no clue how this ended up in my google search :grimacing:)](https://www.cs.cmu.edu/~srini/15-441/S10/lectures/r01-sockets.pdf)
 - [Struct used in lecture](https://www.gta.ufrj.br/ensino/eel878/sockets/sockaddr_inman.html)
 - [Socket/Client applications](https://www.bogotobogo.com/cplusplus/sockets_server_client.php)
 - [Web Server Concepts and Examples](https://www.youtube.com/watch?v=9J1nJOivdyw)
 - [Mozilla HTTP Requests & Responders](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages)
 - [Mozilla HTTP Forwarding](https://developer.mozilla.org/en-US/docs/Web/HTTP/Redirections)
 - [Very clear Poll() guide](https://beej.us/guide/bgnet/html/#poll)
 
 
 ## Contact
 Created by [m-camps](https://github.com/m-camps),
 [xvoorvaa](https://github.com/xvoorvaa),
 [alexdrumi](https://github.com/alexdrumi)
