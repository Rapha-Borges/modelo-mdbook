# Template mdBook 

Este repositório contém um template para criação de livros utilizando o mdBook. 

## Como utilizar

Para utilizar este template, você deve clonar este repositório utilizando o comando:

```
git clone https://github.com/Rapha-Borges/modelo-mdbook.git
```

Editar o arquivo `book.toml` inserindo as informações do seu livro

```
[book]
authors = ["AUTOR"]
title = "TITULO DO SEU LIVRO AQUI"

[output.html]
git-repository-url = "https://github.com/{AUTOR}/{NOME-REPOSITORIO}"
edit-url-template = "https://github.com/{AUTOR}/{NOME-REPOSITORIO}/edit/main/pt/{path}"
cname = "CNAME"
```

Após basta seguir o desenvolvimento do livro conforme a estrutura das diretórios:

```
└─ pt (Diretório padrão para a versão em PT)
|   |─ book.toml (Arquivo de configuração do mdBook)
|   └─ src (Diretório usado para manter todos .md, imagens e demais arquivos que serão referenciados durante o livro)
|   |    └─ BOOKSUMMARY.md (Arquivo com o texto para o “SUMÁRIO”)
|   |    └─ README.md (Arquivo com o texto para o “SOBRE”)
|   |    └─ SUMMARY.md (Arquivo padrão do mdBook que gera os “CAPÍTULOS) 
|   |    └─ Capitulo-X (Diretório de arquivos para cada capítulo respectivamente)
|   └─ theme (Diretório com todos os arquivos de estilização )
|   |      └─ index.hbs (Arquivo para configurção do HTML)
|   |      └─ css (Diretório dos arquivos CSS)
|   |      |    └─ style.css (Arquivo padrão de estilo)
|   └─ translation (Diretório dos arquivos de tradução)
|   |            └─ en (Arquivos em inglês seguindo a estrutura do diretório `src`)
|   |            └─ es ((Arquivos em espanhol seguindo a estrutura do diretório `src`))
└─ home (Diretório da home page)
|     └─ index.html (Arquivo HTML da home page)
|     └─ CSS (Diretório dos arquivos css da home page)
|     |    └─style.css(Arquivo principal de CSS da home page)
```

Para maiores informações de como funciona cada um dos arquivos, basta consultar no próprio repositório desse template, cada arquivo vai contar com uma descrição ou exemplo.

## Como contribuir

Para contribuir com este projeto, siga os seguintes passos:

1. Crie um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Faça o commit de suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o push da branch (`git push origin feature/AmazingFeature`)
5. Abra um pull request
