# Java, Quarkus, Hello, with Dockerfile

```
docker build -f src/main/docker/Dockerfile.jvm -t shared-quarkus .

docker run -i --rm -p 8080:8080 shared-quarkus

curl localhost:8080

<some string> Quarkus 1 12-24-2022 03:39:03 on e29c6975f9e3
```