# NT Store — Ferramentas

## Calculadora de preço de venda (caixa)

`calculadora-precificacao/index.html` — abra no navegador, não precisa instalar nada.

1. Valor de 1 unidade na nota fiscal.
2. Frete total da nota e quantidade total de itens da nota → frete por unidade (frete ÷ itens).
3. Markup (padrão 1,60x) ou margem (padrão 40%).

Preço = (valor na NF + frete por unidade) × markup, ou ÷ (1 − margem), arredondado para cima em ,90.
Os padrões e atalhos ficam no topo do `<script>` (`PADRAO`, `MARKUP_ATALHOS`, `MARGEM_ATALHOS`) e as cores no `:root` do CSS.

## Calculadora completa (gerência)

`calculadora-precificacao/avancada.html` — nota fiscal com vários itens, preço de capa de livros, maquininha, impostos, despesas fixas e markup recomendado.
