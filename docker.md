# How to use the docker container for the course


We provide a docker image [oduerr/tf_docker:cpu_r](https://github.com/oduerr/dl_book_docker) with [Tensorflow](http://www.tensorflow.org) and many other pre-installed python libraries (numpy, pandas).

## Installation of docker

* The official installation guide can be found at: [https://docs.docker.com/engine/installation/](https://docs.docker.com/engine/installation/)



## Running the container
In the docker command line execute:
```{bash}
docker run -p 8888:8888 -p 6006:6006 -it oduerr/dl_book_docker
```
open [http://localhost:8888/?token=tensorchiefs](http://localhost:8888/?token=tensorchiefs) or [http://192.168.99.100:8888/tree?token=tensorchiefs](http://192.168.99.100:8888/tree?token=tensorchiefs)(for some windows versions) in the browser. If you are asked for a password it's `tensorchiefs`

## Running with a linked file system.
For playing with the examples, we recommand cloning the github repository https://github.com/tensorchiefs/dl_book. Alternatively you can also download the zip-file. You then have to point the docker container to the directory. If this is say `~/Documents/workspace/dl_book/` you have to execute:

```
docker run -p 8888:8888 -p 6006:6006 -v ~/Documents/workspace/dl_book/:/notebooks -it oduerr/dl_book_docker
```

## Updating
Please make sure to use the latest container by updating it using 

```
docker pull oduerr/dl_book_docker
```

# Other useful hints for docker

### Starting in bash
In case you want to not start the jupyter notebook sever automatically but want a bash shell do:

```
docker run -p 8888:8888 -p 6006:6006 -it oduerr/dl_book_docker bash
```

### Local vs Inside container
The entry before the colon ':' is on the local machine, the one after it inside the container. Examples:

```








