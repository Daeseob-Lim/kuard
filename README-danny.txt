The files in this folder was cloned from https://github.com/kubernetes-up-and-running/kuard

------------------------
The first example
	- Image without multi-stage

To create and run the Docker image, execute the following commands

$ docker build -t ch02-02a -f Dockerfile.nomultistage .
$ docker run --rm -p 8080:8080 ch02-02a


------------------------
The second example
	- Image with multi-stage



# To create and run the Docker image, run the following commands

$ docker build -t ch02-02b -f Dockerfile .
$ docker run --rm -p 8080:8080 ch02-02b

