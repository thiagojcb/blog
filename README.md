# Um átomo no universo

Blog feito com [Quarto](https://quarto.org), publicado no GitHub Pages pelo GitHub Actions.

- Pré-visualizar localmente: `quarto preview`
- Gerar o site localmente (opcional): `quarto render` (resultado em `docs/`, ignorado pelo git)
- Publicar: `git push` na branch `main`; o workflow `.github/workflows/publicar.yml` faz o resto.

Estrutura:
- `_quarto.yml`: título, menu e aparência do site
- `index.qmd`: página inicial (lista de posts)
- `sobre.qmd`: página "Sobre"
- `posts/<nome>/index.qmd`: cada post; `posts/_metadata.yml`: opções comuns (comentários)
