# TCP/IP CLIENT-SERVER

Simpe Client-Server TCP/IP programs in C.

## Get server IP:

On the command line:

```
hostname -I
```

## Compile and run:

On the server side:

```
gcc -o server server.c
./server
```

On the client side:

```
gcc -o client client.c
./client <IP_of_server>
