# go-graphql

## Carregando os módulos
- go mod tidy

## Na criação do projeto
- go run github.com/99designs/gqlgen init

## Com o projeto já criado
- go run github.com/99designs/gqlgen generate

## Resolvendo o problema de N+1
- DataLoader => Nesta lib utilize o Query Resolution / Resolvers para resolver este tipo de problema
