# hello-world-php

There are some applications which can be used with build image.

```
git clone https://github.com/alauda-devops-quickstarts/hello-world-php.git
s2i build . --context-dir=examples/test-app/ index.alauda.cn/alaudak8s/s2i-php:latest php-test-app
docker run -p 8088:8080 php-test-app
curl 127.0.0.1:8088
```