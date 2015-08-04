A [Docker](https://www.docker.com/) container with

- node 0.12 (latest)
- jdk 1.8.0_51


```bash
# run it

$ docker run -it --rm emmenko/nodejs-java /bin/bash
root@a40b9cf4300a:/# node -v
v0.12.7
root@a40b9cf4300a:/# npm -v
2.13.2
root@a40b9cf4300a:/# java -version
java version "1.8.0_51"
Java(TM) SE Runtime Environment (build 1.8.0_51-b16)
Java HotSpot(TM) 64-Bit Server VM (build 25.51-b03, mixed mode)
```
