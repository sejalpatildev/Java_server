# Web Server Implementation in Java

This repository contains implementations of both **single-threaded** and **multi-threaded** web servers in Java. Each implementation has separate folders containing `Server.java` and `Client.java` files. The servers are tested using Apache JMeter for performance evaluation.

## Features
- **Single-threaded server**: Handles one client at a time.
- **Multi-threaded server**: Uses a thread pool to handle multiple clients concurrently.
- **Timeout handling**: Configurable timeout for client connections.
- **Performance Testing**: JMeter scripts for testing.

## Installation & Usage
### Prerequisites
- Java (JDK 8+)
- Apache JMeter 5.6.3 (my version) 
- make your own jmeter test plan is recommended for no issues

### Running the Single-threaded Server
```sh
cd single-threaded
javac Server.java Client.java
java Server
```

### Running the Multi-threaded Server
```sh
cd multi-threaded
javac Server.java Client.java
java Server
```

### Running the Client
```sh
java Client
```


