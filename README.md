# kaggle-docker
Dockerfile and docker-compose.yml to create kaggle env

```
$ vim ~/.kaggle/kaggle.json # put your kaggle.json
$ chmod 600 ~/.kaggle/kaggle.json
$ git clone https://github.com/shinsuke27/kaggle-docker.git kaggle
$ cd ./kaggle
$ mkdir ./input
$ docker-compose up --build
```
