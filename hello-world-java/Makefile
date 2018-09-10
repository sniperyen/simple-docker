OS = Linux

build:
	s2i build https://github.com/alauda-devops-quickstarts/hello-world-java.git --context-dir=examples/test-app-maven/ index.alauda.cn/alaudak8s/s2i-java:latest java-test-app

run:
	docker run -p 8088:8080 java-test-app