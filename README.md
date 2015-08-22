A [Docker](https://www.docker.com/) container with

- node 0.12
- jdk 1.8.0_51
- chrome for headless testing


```bash
# run it

$ cmd='npm -v && java -version'
$ docker run -it -v $(pwd):/src -w /src emmenko/nodejs-java sh -c "$cmd"
Starting virtual X frame buffer: Xvfb.
Executing command npm -v && java-version
2.11.3
java version "1.8.0_51"
Java(TM) SE Runtime Environment (build 1.8.0_51-b16)
Java HotSpot(TM) 64-Bit Server VM (build 25.51-b03, mixed mode)
```
