microservice:
	GOOS=linux CGO_ENABLED=0 go build -gcflags "-N -l" -o microservice
	docker build -t <YOUR REPO HERE>/microservice:0.1 .
dist:
	docker push <YOUR REPO HERE>/microservice:0.1
