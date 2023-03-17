# Template mdBook 

Este repositório contém um template para criação de livros utilizando o mdBook. 

## Como utilizar

Para utilizar este template, você deve clonar este repositório utilizando o comando:

```bash
git clone https://github.com/Rapha-Borges/modelo-mdbook.git
```

Após basta seguir o desenvolvimento do livro conforme a estrutura das diretórios:

```
└─ pt (Default directory for the PT version)
|   |─ book.toml (mdBook configuration file)
|   └─ src (Directory used to hold all .md, images and other files that will be referenced throughout the book)
|   |    └─ BOOKSUMMARY.md (File with the “SUMMARY” text)
|   |    └─ README.md (File with the “SOBRE” text)
|   |    └─ SUMMARY.md (Standard mdBook file that generates "CHAPTERS") 
|   |    └─ Capitulo-X (File directory for each chapter)
|   └─ theme (Directory with all styling files)
|   |      └─ index.hbs (HTML configuration file)
|   |      └─ css (CSS files directory)
|   |      |    └─ style.css (Default CSS style file)
|   └─ translation (Directory for translations)
|   |            └─ en (English files)
|   |            └─ es (Spanish files)
└─ home (Directory for the home page)
|     └─ index.html (Home page main HTML file)
|     └─ CSS (Directory for the home page CSS files)
|     |    └─style.css(Home page main CSS file)
```

Para maiores informações de como funciona cada um dos arquivos, bas consultar no próprio repositório desse template, cada arquivo vai contar com uma descrição ou exemplo.

## Como contribuir

Para contribuir com este projeto, siga os seguintes passos:

1. Crie um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Faça o commit de suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o push da branch (`git push origin feature/AmazingFeature`)
5. Abra um pull request