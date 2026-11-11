# Quiz Recife — Observatório de Turismo do Recife

Quiz de 20 perguntas sobre história, cultura e turismo do Recife, com layout pensado para celulares e a identidade visual do Observatório de Turismo do Recife.

## Como usar

É uma página estática: basta abrir o `index.html` no navegador ou publicar com o GitHub Pages
(Settings → Pages → Branch `main`, pasta `/ (root)`).

## Estrutura

- `index.html` — página do quiz (perguntas, estilos e lógica no mesmo arquivo)
- `assets/` — logotipo e símbolo do Observatório

## Editar perguntas

As perguntas ficam no array `PERGUNTAS` dentro do `index.html`. Cada item tem o texto (`q`), as alternativas (`o`) e o índice da resposta certa (`r`, começando em 0: A=0, B=1, C=2, D=3, E=4).
