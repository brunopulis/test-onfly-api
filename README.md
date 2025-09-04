# Teste de API via Postman

O teste foi executado via Postman, porém, importei a **collection** e a variável de ambiente.

## Pré requisito

Instale as depedências com o comando:

```sh
 npm install
```

## Execute o Newman

O projeto utiliza o Newman para gerar um relatório HTML das requisições da API.
Para utilizar use o comando:

```sh
 newman run users.json -e dev.json --reporters=cli,htmlextra
```

O relatório fica armazenado dentro do diretório **newman**.
