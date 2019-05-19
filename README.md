# ierg4180_asg2

## How to run

After cloning the project,
Please open your shell, and input

```
cd {PROJECT_PATH}
```

then make the project
```
make
```

run the server
```
./server -stat 1000 -lhost localhost -lport 4180 -sbufsize 1000 -rbufsize 1000
```

run the client
```
./client -recv -stat 1000 -rhost localhost -rport 4180 -proto tcp -pktsize 1000 -pktrate 2500 -pktnum 100 -sbufsize 1000 -rbufsize 1000
```
