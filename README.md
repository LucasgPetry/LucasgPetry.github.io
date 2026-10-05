# Lucas Petry — Portfolio / GitHub Pages

Portfólio estático desenvolvido para a **Entrega Intermediária da disciplina Bootcamp I**, com foco em apresentação profissional, integração com GitHub/LinkedIn e publicação via GitHub Pages.

## Objetivo

Apresentar, de forma objetiva e profissional:

- perfil e posicionamento profissional;
- formação e stack técnica;
- projetos acadêmicos/pessoais selecionados;
- links para GitHub, LinkedIn e contato;
- evidências e resultados documentados nos projetos.

## Stack do site

- HTML5 semântico
- CSS3 responsivo com tema claro/escuro
- JavaScript vanilla
- GitHub Pages

Não há framework, processo de build ou dependências obrigatórias.

## Estrutura

```text
.
├── index.html
├── 404.html
├── README.md
├── CHANGELOG.md
├── robots.txt
├── sitemap.xml
├── .nojekyll
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   └── img/
│       └── favicon.svg
└── extras/
    └── README_PROFILE_SUGGESTED.md
```

## Executar localmente

Você pode abrir `index.html` diretamente no navegador. Para testar em ambiente HTTP local:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Publicar no GitHub Pages

A opção recomendada é criar um repositório público chamado exatamente:

```text
LucasgPetry.github.io
```

Em seguida:

```bash
git init
git add .
git commit -m "feat: publica portfolio v1.0"
git branch -M main
git remote add origin https://github.com/LucasgPetry/LucasgPetry.github.io.git
git push -u origin main
```

No GitHub, abra **Settings > Pages** e configure:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

A URL esperada será:

```text
https://lucasgpetry.github.io/
```

## Versionamento sugerido para a disciplina

Crie uma tag da primeira versão:

```bash
git tag -a v1.0.0 -m "Portfolio Bootcamp I - versão 1.0"
git push origin v1.0.0
```

Depois, para alterações visuais ou textuais:

```bash
git checkout -b feature/ajuste-portfolio
# faça as mudanças
git add .
git commit -m "refactor: melhora apresentação dos projetos"
git push -u origin feature/ajuste-portfolio
```

## Integração com LinkedIn

Após a publicação, adicione no LinkedIn:

1. o link do GitHub Pages na seção **Destaques**;
2. os principais projetos na seção **Projetos**;
3. o GitHub no campo de contato ou Destaques;
4. o link do portfólio também no README do perfil GitHub.

## Conteúdo utilizado

As informações do site foram organizadas a partir do perfil GitHub, documentação dos repositórios e dados profissionais previamente consolidados. Resultados numéricos aparecem somente quando estavam documentados nos respectivos projetos.
