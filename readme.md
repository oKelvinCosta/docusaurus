Projeto para testar o docusaurus

[Demo](https://keepachangelog.com/en/1.0.0/),

# Subir para gh-pages automático

Pré-requisitos:

- Conta no GitHub.
- Git instalado na sua máquina.
- Ter NodeJS e Npm instalado na sua máquina.

Repositório já deve existir Localmente e no Github.

Todos os comandos, rodar no terminal, na pasta que há o `Package.json`

```
npm install gh-pages --save-dev
```

No package.json em `Scripts`:

```

https://okelvincosta.github.io/docusaurus/
"predeploy": "npm run build",
"deploy": "gh-pages -d build"

```

**Rodar `npm run build`**

O comando criará uma branch **gh-pages** com o conteúdo do build dentro.

# Changelog

O formato segue [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

## [1.0.5] 11-09-2019

### Adição :rocket:

- Tutorial no readme para deploy no gh-pages
- Sistema de deploy para gh-pages

## [1.0.2] 11-09-2019

### Adição :rocket:

- Url do Github.io

## [1.0.1] 11-09-2019

### Adição :rocket:

- Início da implementação Algolia.
- 2 páginas de documentação.
- Modelo padrão do Docusaurus modificado.

## Ícones

### Adição :rocket:

### Atualização :pushpin:

### Correção :wrench:
