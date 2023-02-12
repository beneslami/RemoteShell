# RemoteShell

This is a server program that provides remote shell for the client. The server acts like 
a SSH server but without key distribution. to run the server, simply give a port as an input 
to it.
```
./main 4444
```

to test the server you can either write a TCP client program that connects to the server
or simply using ```nc``` as below:
```
nc [IP ADDRESS] 4444
```