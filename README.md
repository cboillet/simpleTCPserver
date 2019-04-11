# simpleTCPserver
c++ TCP server for streaming


### Build
```bash
g++ client.cpp -o client libboost_system.a
g++ async_server.cpp -o async_server libboost_system.a
```

boost library had to be build from sources

### Run
```bash
  ./async_server
  ./client
```

### Futur dev

Change message member in the connection class as a reference to the 3D keyPoints.

