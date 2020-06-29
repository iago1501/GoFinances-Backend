Projeto criado para o desafio do módulo 2 da rocketseat, Database upload.
Projeto a ser criado no desafio será o GoFinances

## Configuraçõs Iniciais

Para a criação do banco de dados foi utilizado o docker com uma imagem do Postgres,
rodando na porta 5432. As demais configurações podem ser encontradas no arquivo ormconfig.json

OBS: A database utilizada foi: gostack_desafio06,
e sua equivalente para testes: gostack_desafio06_tests

## Scripts disponíveis

Para rodar o projeto basta executar

### `yarn`

Para instalar todas as dependências de pacotes do NPM

### `yarn typeorm migration:run`

Para criar a estrutura do banco de dados pré definida nas models,
que foi modelada nas migrations

### `yarn dev:server`

Roda a aplicação em modo de desenvolvimento.<br />
Abra [http://localhost:3333](http://localhost:3333) para ver o projeto no browser.

### `yarn test`

Para executar os testes necessários para a aplicação ser considerada criada com sucesso

## Fundamentos

Neste projeto foram colocados em prática os conhecimentos adquiridos no módulo 2 do curso de Node,
com um foco maior na implementação do banco de dados na aplicação e da utilização do ORM (TypeORM), assim como todos os fundamentos aprendidos no desafio número 5, onde foram abordados conceitos
do SOLID

- Models;
- Repositories;
- Services;
- DTO;
- Interface;
- Typescript;
- Routes;
- TypeORM;
- Migrations;
- csvParse;
- Multer;
- Docker;
- Exception Handler;
- Middlewares;
