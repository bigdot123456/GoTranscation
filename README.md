# TxSend-Sign-Demos
account creation, as well as transaction build and sign
# GoTranscation

```bash
export GO111MODULE=on
go mod init TxSend-Sign-Demos
cat go.mod
go run serverdemo.go

``` 

change go.mod version from matrixai 1.1.4 to 1.1.0 
then use the following to update
```bash
go mod tidy
go mod download
go mod vendor
go mod verify
go build src/demo/main.go

 ```

*** Anotaazfgher method 
run in command line  
then start debug  

