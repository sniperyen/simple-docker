OS = Linux

build:
	s2i build https://github.com/alauda-devops-quickstarts/hello-world-php.git --context-dir=examples/test-app/ index.alauda.cn/alaudak8s/s2i-php:latest php-test-app

run:
	docker run -p 8088:8080 php-test-app