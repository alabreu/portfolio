# portfolio

Portfólio web de **Alexandre Oliveira Abreu** — design gráfico, ilustração,
desenho industrial e identidade visual.

Site estático (HTML/CSS/JS), sem build. Antes ficava na raiz de
`alabreu.github.io`; migrado para este repositório dedicado.

## Publicação (GitHub Pages)

Servido pelo GitHub Pages a partir do branch `main` (raiz do repositório).
Para ativar: **Settings → Pages → Source: `main` / `/ (root)`**.

URL: https://alabreu.github.io/portfolio/

O arquivo `.nojekyll` desliga o processamento Jekyll (servimos os arquivos
como estão).

## Estrutura

- `index.html` — entrada (logo → `home.html`)
- `home.html` — grid de seções
- `cv.html`, `drawing.html`, `illustration.html`, `others.html`,
  `publishing.html`, `visualID.html` — seções do portfólio
- `css/`, `js/`, `images/` — assets (links relativos; funcionam sob `/portfolio/`)
