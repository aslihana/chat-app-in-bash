# chat-app-in-bash

## Usage
To start, create one tab for server, other(s) for client(s).
### Running the app 
Change the directories to the codes located directory on all tabs. 

Write `gcc -Wall -g3 -fsanitize=address -pthread server.c -o server` , `./server 4444 ` on server's tab.

Write `gcc -Wall -g3 -fsanitize=address -pthread client.c -o client` , `./client 4444` on the client(s)' tab.

For exit, just write `exit` to the chat.

## Example Of Use
![Screenshot from app](ss.png)