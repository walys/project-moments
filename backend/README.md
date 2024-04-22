# Backend - Setup  api do projeto moments

## Passo a passo para rodar o projeto backend

### Após clonar o projeto entra na pasta 
```sh
cd project-moments\backend\curso_adonis_api_yt-main
```
### Execute o seguiinte comando para instalar todas a dependências
```sh
npm install
```
### Gere uma generate key para inicialização do projeto
```sh
node ace generate:key
```
### Copie e cole no mesmo diretorio o arquivo .env.example e renomei para .env

### Execute as migrations para criar as tabelas no banco de dados no db.sqlite3
```sh
node ace migration:run
```
### O projeto está pronto para ser executado, a api podera ser executada nesse endpoint via get: http://127.0.0.1:3333/api/moments
```sh
node ace serve
```

