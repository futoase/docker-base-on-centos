Docker base on CentOS
---------------------

Base image is CentOS 6.5 x86_64.

# Setup on Mac OS X?

- required software is [homebrew](http://brew.sh/).

```
> brew bundle
> vagrant up --provision
> vagrant ssh # connect to vagrant box.
```

# set environment for DOCKER_HOST on your machine.

```
> export DOCKER_HOST="tcp://192.168.33.111:4243"
> docker ps # connect of docker client from docker daemon on vagrant box.
```

# Author
2014 (c) Keiji Matsuzaki

# License
MIT.
