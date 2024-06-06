# Recurso EW 2024

## Setup

1. Trocar "bookId" por "_id"
2. Remover o '[]' do inicio do ficheiro
3. Converter de lista (em forma de string) para lista (com ajuda de regex no find and replace)
4. Trocar os \" e ' para apenas "
5. Converter alguns campos para número em vez de string
6. mongoimport -d livros -c livros datasetNovo.json

## HTML
decidi escolher o nome do autor para fazer de ID, por simplicidade