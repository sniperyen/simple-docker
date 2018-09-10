OS = Linux

build:
	s2i build https://github.com/alauda-devops-quickstarts/hello-world-python.git --context-dir=examples/setup-test-app/ index.alauda.cn/alaudak8s/s2i-python:2.7 python-test-app

run:
	docker run -p 8088:8080 python-test-app