# 🎬 App de Filme Aleatório
Colaboradores: João Francisco Brandino e Samuel Porto de Vasconcelos

Este é um aplicativo simples feito em Flutter (ou insira o framework correto) que exibe um **filme aleatório** na tela, utilizando dados de um arquivo JSON.

## 📦 Funcionalidades

- Exibe um filme aleatório a cada inicialização.
- Carrega dados de um arquivo JSON local.
- Mostra informações como: título, ano, gênero e descrição do filme.

## 📂 Estrutura do JSON

O app lê os filmes a partir de um arquivo chamado `documentario.json` no seguinte formato:

```json
[
  {
    "titulo": "A Origem",
    "ano": 2010,
    "genero": "Ficção Científica",
    "descricao": "Um ladrão que rouba segredos corporativos através do uso da tecnologia de compartilhamento de sonhos."
  },
  {
    "titulo": "O Senhor dos Anéis: A Sociedade do Anel",
    "ano": 2001,
    "genero": "Fantasia",
    "descricao": "Um jovem hobbit embarca em uma jornada para destruir um poderoso anel."
  }
]
