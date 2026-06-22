
Generate files:
```bash
protoc --go_out=gen/go/orchestrator/v1 --go_opt=paths=source_relative --go-grpc_out=gen/go/orchestrator/v1 --go-grpc_opt=paths=source_relative proto/orchestrator/v1/register.proto
```