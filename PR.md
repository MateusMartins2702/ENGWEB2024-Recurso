# Recurso EW 2024

## Setup

Em primeiro logar  troquei "bookId" por "_id"
A seguir removi o '[]' do inicio do ficheiro
Converti ainda de lista (em forma de string) para lista (com ajuda de regex no find and replace)
De seguida troquei os \" e ' para apenas "
E para finalizar ainda converti alguns campos para número em vez de string


Após tudo isto correr no terminal: mongoimport -d livros -c livros datasetNovo.json

## HTML
Para tornar mais simples optei por escolher o nome do autor para fazer de ID.