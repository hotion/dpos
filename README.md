# Implement a simple blockchain use dpos algorithm
 <a href="https://travis-ci.org/csunny/dpos"><img src="https://travis-ci.org/csunny/dpos.svg?branch=master" /></a>

## Architecture Design
- Create a P2P Conn-pool
- BlockChain Generate
- Node Manage And Vote
- Pick Node
- Write Block On Blockchain


## RUN 
```
git clone git@github.com:csunny/dpos.git

cd dpos    //  change to source code path 
go build main/dpos.go  -o dpos
```

connect multi peer 
```
./dpos new --port 3000 --secio
```
## Vote
```
./dpos vote -name QmaxEdbKW4x9mP2vX15zL9fyEsp9b9yV48zwtdrpYddfxe -v 30
```

# Document
[Doc](https://xiaozhuanlan.com/topic/3245810967)

# Licence 
MIT
