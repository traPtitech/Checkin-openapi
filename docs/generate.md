# 生成手順

## Server

`server` ディレクトリがなければ作成してください。
その後

```bash
go run github.com/oapi-codegen/oapi-codegen/v2/cmd/oapi-codegen@latest -config oapi-codegen.yaml openapi.yaml
```

を実行すると `server/gen.go` が生成されます。
