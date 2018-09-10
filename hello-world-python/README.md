# hello-world-python

There are some applications which can be used with build image.

```
git clone https://github.com/alauda-devops-quickstarts/hello-world-python.git
s2i build . --context-dir=examples/setup-test-app/ index.alauda.cn/alaudak8s/s2i-python:2.7 python-test-app
docker run -p 8088:8080 python-test-app
curl 127.0.0.1:8088
```