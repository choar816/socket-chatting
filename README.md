# socket-chatting

- Server 컴파일 및 실행 방법

`gcc -o server server.c -lpthread`

`./server 9999`

- Client 컴파일 및 실행 방법

`gcc -o client client.c`

`./client 127.0.0.1 9999 [name]`
