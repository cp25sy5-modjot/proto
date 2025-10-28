# cp25sy5-modjot/proto

Protocol buffers for ModJot microservices.

- Module: `github.com/cp25sy5-modjot/proto`
- Stubs: `github.com/cp25sy5-modjot/proto/gen/ai/v1` (package `aiwpb`)

## Regenerate
```bash
brew install protobuf
go install google.golang.org/protobuf/cmd/protoc-gen-go@latest
go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest

protoc -I=.   --go_out=. --go_opt=paths=source_relative   --go-grpc_out=. --go-grpc_opt=paths=source_relative   ai/v1/ai.proto
```
