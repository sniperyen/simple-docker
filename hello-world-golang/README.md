# hello-world-golang

There are some applications which can be used with build image.

```
git clone https://github.com/alauda-devops-quickstarts/hello-world-golang.git
s2i build . --context-dir=examples/simple-app/app index.alauda.cn/alaudak8s/s2i-golang:1.8 golang-test-app
docker run -p 8088:8080 golang-test-app
curl 127.0.0.1:8088
```