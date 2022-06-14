Ambiente de desenvolvimento: NodeJS, NPM e MySQL

express => framework que facilita o desenvolvimento de aplicações backend, possuindo um conjunto de templates para aplicações full-stack;

dotenv => possibilita a leitura do arquivo .env;

cors => especificação da w3c para trabalhar com API. Permite acessos de outros sites, mesmo estando em domínios diferentes;

body-parser => Modulo capaz de converter o body da requisição em outros formatos;



Configuração API:
- npm init -y | yarn init -y;
- npm install express mysql dotenv cors body-parser | yarn add express mysql dotenv cors body-parser;
- npm install nodemon --save-dev | yarn add nodemon -D;
- criar pasta src;
- criar arquivo variaveis.env => armazenar variaveis do sistema(ex.: porta, string de conexão com banco de dados, usuário, senha ... );
- criar arquivo server.js em src;
- configurar script "start" para abrir nodemon e arquivo server.js;


Script criação banco de dados no mysql

```sql
create database dbApiCarros;
use dbApiCarros;
create table carros (
	codigo int primary key auto_increment,
	modelo varchar(30),
	placa varchar(7)
);
```

