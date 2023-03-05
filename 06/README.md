## Compile
```
g++ -Wall -Wextra -O2 -g 06_server.cpp -o server
g++ -Wall -Wextra -O2 -g 06_client.cpp -o client
```

## Run
```
$ ./server
$ ./client
```

## Output
### Server 
```
./server
client says: hello1
client says: hello2
client says: hello3
EOF
```

### Client
```
server says: hello1
server says: hello2
server says: hello3
```