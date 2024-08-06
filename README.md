# Proto Instructions

### 1. Install the Updates

Run the following command to tidy up the module dependencies:

```bash
go mod tidy
```

### 2. Compile proto files


```bash
protoc --go_out=. --go-grpc_out=. protofiles/*.proto
```


go get github.com/reodotdev/proto/protofiles@v0.1.0