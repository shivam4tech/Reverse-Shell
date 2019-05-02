# Overview
This is a client-server based reverse terminal creation project. Through this debugging and terminal access can be easily done at client side just by making client connect to a remote server. 

* **server.py** - runs on a public server and waits for clients to connect
* **client.py** - connects to a remote server and then wait for commands

***

## Server

To set up server script, simply run **server.py** using Python 3.4

`python3 server.py`

Then server can easily run windows terminal queries.

***

## Client

In **client.py**, first change the IP address to that of the server and then run on target machine. 
Two ways to run client file are:
1-> Run client.py file directly if the system at client side has python 3.7 installed.
2-> If client does not have a compatible version of Python installed, run client.exe file present inside the build folder.

## What I have learned
1-> Socket programming
2-> Client Server architecture
3-> Creating executable files for windows environment
