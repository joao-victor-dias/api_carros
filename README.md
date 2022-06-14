# API-Carros
A API tem como funções ler, adicionar, editar e deletar dados de carros no banco de dados.

## Tecnologias Utilizadas
<div>
	<img align="center" height="90" width="110" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-plain-wordmark.svg" />
	<img align="center" height="90" width="110" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />
	<img align="center" height="90" width="110" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/yarn/yarn-original-wordmark.svg" />

</div>

## Dependências
- **express:** framework que facilita o desenvolvimento de aplicações backend, possuindo um conjunto de templates para aplicações full-stack;
- **dotenv:** possibilita a leitura do arquivo .env;
- **cors:** especificação da W3C para trabalhar com API. Permite acessos de outros sites, mesmo estando em domínios diferentes;
- **body-parser:** módulo capaz de converter o body da requisição em outros formatos;
- **nodemon (desenvolvimento) :** biblioteca que ajuda no desenvolvimento de sistemas com NodeJS reiniciando automaticamente o servidor quando ocorre alterações.

## Query de criação do banco de dados no MySQL

```sql
create database dbApiCarros;
use dbApiCarros;
create table carros (
	codigo int primary key auto_increment,
	modelo varchar(30),
	placa varchar(7)
);
```


