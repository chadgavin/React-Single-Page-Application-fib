# React-Single-Page-Application-fib
Using React to create a single page application of the fib sequence with user input

## To use, clone git repository
``` git clone https://github.com/chadgavin/React-Single-Page-Application-fib.git``` 

## Next  build the docker container with tagging named client
``` docker build --tag client . ```

## Run the docker container with forwarding of port to port 300
```docker run -it -p 80:3000  client```

## Quit the contianer after finish
``` docker stop client```
