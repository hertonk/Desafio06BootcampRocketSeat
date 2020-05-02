# Resolução do Desafio 06 - GoStack

<h3 align="center">
  Desafio 06: Database upload
</h3>

## Descrição

Resolução do Desafio 06 do Bootcamp da RocketSeat.

### Testando a resolução

Para utilizar a resolução do desafio, você deve baixar este repositório rodar o comando `yarn` para a instalação das dependências e para "rodar" o back-end deve utilizar o comando `yarn dev:server`.

Abaixo segue uma descrição das rotas:

- **`GET /transactions`**: Essa rota é responsável por exibir a lista de todas as transações cadastradas na aplicação e ao final exibe um balanço das entradas e saídas.

- **`POST /transactions`**: Essa rota tem como objetivo cadastrar novas transações, é necessário enviar no corpo da requisição (body) os seguintes parâmetros: `title`, `value`, `type` e `categoy`. Em `type` deve-se especificar se é um depósito `income` ou um saque `outcome`.

- **`POST /transactions/import`**: Essa rota tem como objetivo cadastrar novas transações por meio da importação de um arquivo .csv, é necessário enviar o arquivo identificado de `file`. Um arquivo exemplo de importação pode ser encontrado em `__tests__/import_template.csv`.

- **`DELETE /transactions/:id`**: Essa rota tem como objetivo apagar uma transação, deve ser passado o `id` da transação nos parametros da rota.


---

Feito por Herton F. Vilarim.
