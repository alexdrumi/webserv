<div align="center">
  <a href="https://github.com/alexdrumi/webserv">
    <img src="data/www/webserver.jpg" alt="MNE EEG Logo" width="550" height="250">
  </a>
</div>


# Habit Tracker CLI
A Habit Tracker CLI application built with Django that leverages OOP and design pattern principles to manage users, habits, goals, progress, and reminders.


<br>

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Contact](#contact)


## General Information
Habit Tracker CLI is a command-line application that helps users monitor and improve their daily habits. It uses Django as its backend framework and implements object-oriented design patterns—such as the repository, service, and controller patterns—to ensure the code is modular, testable, and maintainable. The project allows you to:<br>

- Create, update, and delete user accounts.<br>
- Set up daily or weekly habits..<br>
- Define goals for each habit.
- Track progress with timestamps and streak calculations.
- Generate reminders and perform basic analytics.

.<br>


## Technologies Used
- Python 3.8+ – Primary language for the CLI and business logic.
- Django – Backend framework for managing models and migrations.
- MySQL/MariaDB – Database engine.
- Click - For building the command-line interface.
- Pytest - Unit testing framework for all repositories/services.
  


## Features
- User Management: Create, update, delete, and validate users.
- Habit Management: Add and modify daily/weekly habits.
- Goal Setting: Define goals for each habit.
- Progress Tracking: Record progress entries with timestamps and compute streaks.
- Reminders & Analytics: Set up reminders and view habit analytics.
- CLI Interface: Interact with the application through a command-line interface.




- Directory listing


## Screenshots
![Example screenshot](./data/www/screenshot.png)



## Setup
Requirements are:
- Docker
- Python 3.8



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
