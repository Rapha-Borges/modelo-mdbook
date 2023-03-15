# mdBook Template

This repository contains a template for creating books using mdBook.

## How to use

To use this template, you must clone this repository using the command:

```bash
git clone https://github.com/Rapha-Borges/modelo-mdbook.git
```

Then just follow the development of the book according to the structure of the directories:

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
|   |           └─ style.css (Default CSS style file)
|   └─ translation (Directory for translations)
|                └─ en (English files)
|                └─ es (Spanish files)
└─ home ()
      └─ index.html ()
      └─ CSS ()
      |    └─style.css()
```

For more information on how each of the files works, just consult the repository of this template, each file will have a description or example.



## How to contribute

To contribute to this project, follow these steps:

1. Create a fork of the project
2. Create a branch for your featurejet (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request