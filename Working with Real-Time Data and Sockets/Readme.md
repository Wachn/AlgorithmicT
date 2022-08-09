Real-time processing of data and decision making based on the streaming data is a necessity. This chapter
is about working with real-time data for which sockets are in general the technological tool of choice.

1. Network socket\
Endpoint of a connection in a computer network; socket for short\
2. Socket address\
Combination of an Internet Protocol (IP) address and a port number   
3. Scoket pair\
Combination of a local and a remote socket that communicates with each other
4. Socket API\
The application programming interface allowing for the controlling of sockets and their comminucations
   
* Focuses on the use of [ZeroMQ](http://zeromq.org) as a lightweight, fast, and scalable socket programing library
    * *Publisher-subscriber* (PUB-SUB) pattern where a single socket publishes data and multiple sockets simultaneously retrieve the data
    * Retrieval of real-time financial data from an exchange, a trading platform, or a data service provider
    
**Chapter Content**
1. Running a Simple Tick Data Server
2. Connecting a Simple Tick Data Client
3. Signal Generation in Real Time
4. Visualizing Streaming Data with [Plotly](http://plot.ly)

*This chapter heavily utilise ports over which socket communication takes place and requires the simultaneous
execution of two or more scripts at the same time. It is therefore recommended to execute the codes in this chapter in differnet terminal instances, running different 
Python kernels. Hence, execution with Jupyter notebook will not work.*
