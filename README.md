# Pre-compiling a go application on Linux to run on ARM, in a docker container. 

Cross-compile the test.go application with `env GOOS=linux GOARCH=arm GOARM=5 go build test.go`.