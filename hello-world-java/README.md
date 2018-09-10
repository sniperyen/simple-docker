# hello-world-java

There are some applications which can be used with build image.

```
git clone https://github.com/alauda-devops-quickstarts/hello-world-java.git
s2i build . --context-dir=examples/test-app-maven/ index.alauda.cn/alaudak8s/s2i-java:latest java-test-app
docker run -p 8088:8080 java-test-app
curl 127.0.0.1:8088
```