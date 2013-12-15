docker-gitbucket
================

Dockerfile for https://github.com/takezoe/gitbucket


## Usage

    $ git clone git clone git@github.com:essa/docker-gitbucket.git
    $ cd docker-gitbucket
    $ sudo docker build -t essa/docker-gitbucket - < Dockerfile
    $ mkdir data # create data directory
    $ sudo docker run -d -p 2022:22 -p 8080:8080 -v `pwd`/data:/home/gitbucket/data:rw essa/docker-gitbucket



