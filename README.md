# Task List

## O projeto consiste em uma aplicação Full Stack completa com o objetivo de auxiliar no gerenciamento de atividades e tarefas.

<br>
<br>
<br>
 
# Tecnologias Utilizadas

## Backend


- <a href="https://nodejs.org/en/"> NodeJS</a><img align="center" alt="NodeJS" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg">
- <a href="https://expressjs.com/">Express</a><img align="center" alt="Express" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg">

## Frontend

- <a href="https://www.w3schools.com/html/">HTML</a><img align="center" alt="HTML" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">

- <a href="https://www.w3schools.com/css/">CSS</a><img align="center" alt="CSS" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">

- <a href="https://www.javascript.com/">JavaScript</a><img align="center" alt="JavaScript" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">

## Database

- <a href="https://www.mysql.com/">MySQL</a><img align="center" alt="MySQL" height="20" width="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">

<br>

# Como usar

### Primeiro, precisamos clonar ou baixar este repositório.

```bash
#Command to clone the repository

$ git clone https://github.com/danielginez/todolist-fullstack
```

### Após clonar o repositório, é necessário criar um banco de dados MySQL junto com as colunas necessárias.

```bash
#Command to create a database in the MySQL terminal:

$ CREATE DATABASE database_name;
```

### A seguir é necessário criar a tabela de “tarefas” que será utilizada pela aplicação.


```bash
#Command to create the table with its columns

$ CREATE TABLE tasks(
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(45) NOT NULL,
    status VARCHAR(45) NOT NULL,
    created_at VARCHAR(45) NOT NULL
);
```

### Na raiz do projeto existirá um arquivo chamado ".env.example" este arquivo contém 5 campos que deverão ser preenchidos em um arquivo chamado ".env", basta criar este arquivo ou renomear o arquivo de exemplo. Depois disso, basta preencher os campos com os dados referentes ao seu banco de dados.

```bash
PORT= [Port the server will run on]
MYSQL_HOST= [The host of your machine, by default is 'localhost']
MYSQL_USER= [Your username, by default MySQL uses the 'root' user]
MYSQL_PASSWORD= [The password you chose when installing MySQL]
MYSQL_DB= [The name of the database created earlier.]
```

### Antes de iniciar a aplicação, precisamos instalar o 'node_modules' e para isso basta abrir um terminal na pasta "backend" (é aconselhável utilizar o terminal do editor/IDE).

```bash
#Command to download the 'node_modules'

$ npm install
```

### Por fim, basta executar o comando para iniciar o servidor (ainda dentro da pasta “backend”) e abrir o arquivo “index.html”.

```bash
#Command to start the server.

$ npm start
```

<br>

# Credits to

### Daniel Boaventura
