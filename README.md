# Three Way Handshake

π» An example of a TCP-Handshake (Three-Way-Handshake) written in Python.  

π TCP uses a three-way handshake to establish a reliable connection. The connection is full duplex, and both sides synchronize (SYN) and acknowledge (ACK) each other. The exchange of these four flags is performed in three stepsβSYN, SYN-ACK, and ACK.

### π Scheme :
<img src="https://github.com/4m4Sec/Three-Way-Handshake/blob/main/tcp-handshake.jpg">

### π Example :
<img src="https://github.com/4m4Sec/Three-Way-Handshake/blob/main/example.png">

### π How to start it ?
Open two differents shells and run the files in each shell.  
Run the <a href="https://github.com/4m4Sec/Three-Way-Handshake/blob/main/server.py">server.py</a> file before the <a href="https://github.com/4m4Sec/Three-Way-Handshake/blob/main/client.py">client.py</a> file.
```
python3 server.py
```
```
python3 client.py
```