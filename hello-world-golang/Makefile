OS = Linux

build:
	s2i build https://github.com/alauda-devops-quickstarts/hello-world-golang.git --context-dir=examples/simple-app/app index.alauda.cn/alaudak8s/s2i-golang:1.8 golang-test-app

run:
	docker run -p 8088:8080 golang-test-app