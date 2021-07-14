# depot-simulator
A Multi-Threaded Peer-To-Peer C Program That Simulates A Depot And Connects To Neighbours In The Network

## Overview 
This program implements a network simulation. 2310depot is a single peer-to-peer, multi-threaded C99 program. Multiple instances of this program will execute to form this network.

### How to run
The "make" command will create an executable named 2310depot.
Running it will print the port number to connect to.
Then on a different shell, netcat can be used to connect to the port by using:

```sh
nc localhost PORTNUMBER
```

Furthermore, a new instance of 2310depot can also connect to that port by the command:

```sh
CONNECT:PORTNUMBER
```

### More Info
The program is based on very specific functionalities that were mentioned in an assignment specification. If you are interested or should you require more information on any aspect of it, feel free to email me (mujibulislamdipto@gmail.com).
I will send you a copy of the spec and provide further explanation if required.
