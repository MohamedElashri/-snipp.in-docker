# snipp.in-docker
Docker build for  [snipp.in](https://github.com/haxzie/snipp.in) snippet manager


## Usage
You can use snipp.in from docker, you can build your own image using 

```
docker build -t snipp/snipp.in .
```

To depoly an snipp.in instance using docker container you can run the following: 

```
docker run -it -p 80:80 snipp/snipp.in .
```

You can change the host binding port from `80` to other ports. 

Now to access the instance you can go to browser and write `http://localhost` or your `ip:port` if you deploy on a vps (public instance) and changed the host binding port.



