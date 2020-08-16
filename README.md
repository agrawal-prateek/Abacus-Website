# ABACUS website

To start this website's server you will need following system are required

	- LINUX 64 bit

To start this website's server you will need following components to be installed on your linux machine

	- NODE.JS 6 or above
	- NPM 4 or above
	- Redis- server 3.2.9 or above
	- mysql 5/ mariaDB 10


Then you will need to setup database. For this open mysql command prompt in project's root directory and make a database named "project" by typing following commands:

	create database project

Then import whole database table by typing following command:

	source DBScripts/project

To start the servers open TERMINAL/ BASH in root directory of this project

Then type the following command to start node.js server:

	node main.js

If node server successfully starts then you will need to start redis server and you will need to give root access. To start redis-server type following commands:

	sudo redis-server

For any query, feel free and contact me



Wrote with ❤️ by [Prateek Agrawal](https://www.linkedin.com/in/agrawal-prateek/)
