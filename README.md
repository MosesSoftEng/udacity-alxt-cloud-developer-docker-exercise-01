# Your First Docker App Exercise
Containerize a node.js application using docker.



## Commands used
Run node.js app

```npm install```

```node server.js```

Build docker image
```docker build -t simple-node .```
docker build –t simple-node -f simple_node_dockerfile

Run docker container with the built docker image
```docker run f9ec83eec9f4```

Stop running docker container
```docker ps```
```docker kill 41c3cd205e4c```

