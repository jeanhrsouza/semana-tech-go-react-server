## Adicionar as dependencias que faltam
```bash
go mod tidy
```

## Executar docker e verificar logs
```bash
docker compose up
```

## Executar docker sem verificar logs
```bash
docker compose start
```

## executar as migrations
```bash
go run cmd/tools/terndotenv/main.go
```

## verificar banco de dados
- localhost:8081


## utilizando o generate
```bash
 go generate ./...
```

