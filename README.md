# altf4teste
API Produtos para avaliação ALT + F4 Tecnologia criada em Java


## Requisitos:

Java 1.8, Spring Boot, JPA, PostgreSQL

## Iniciando

Efetue o clone deste repositório

```
git clone https://github.com/alassse/altf4teste.git
```

Logo após, instale as dependências pelo Maven

## Insira os dados de acesso a uma base de dados
Local:
resources/application.properties

## Execute os scripts .SQL
Local:
resources/produtos.sql

## Inicie o servidor

## Teste "Listar todos os produtos"

No [Postman](https://www.getpostman.com/downloads/) ou no navegador, insira a URL http://localhost:8080/produtos com o verbo HTTP GET

## Teste "Listar um produto (pelo ID)"

No [Postman](https://www.getpostman.com/downloads/) ou no navegador, insira a URL http://localhost:8080/produtos/{id} com o verbo GET.

## Test "Criar um produto"

No [Postman](https://www.getpostman.com/downloads/), com a URL http://localhost:8080/produtos com o verbo POST e envie o produto a ser criado, conforme exemplo:
{
    id: 000,
		codigo: 0000,
		nome: "XXXXXXX",
		valor: 000000,
		marca: "XXXXXXX"
}

## Teste "Editar um produto"
No [Postman](https://www.getpostman.com/downloads/), insira a URL http://localhost:8080/{id} com o verbo PUT e envie o produto a ser criado, conforme exemplo:
{
    id: 000,
		codigo: 0000,
		nome: "XXXXXXX",
		valor: 000000,
		marca: "XXXXXXX"
}

## Teste "Excluir um produto"
No [Postman](https://www.getpostman.com/downloads/), insira a URL http://localhost:8080/{id} com o verbo DELETE;
