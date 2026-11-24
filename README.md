# Binder Master Set: Zeraora & Meowth

Binder digital para acompanhar uma coleção de cartas do Pokémon Estampas Ilustradas (TCG) em português. Ele reúne todas as versões do Zeraora e do Meowth lançadas no Brasil, com cada bolso do binder representando uma versão da carta (normal, foil, reverse foil e paralelas).

**Acesse:** https://yuricostaa.github.io/binder-pokemon-tcg/

## Funcionalidades

- 113 bolsos (42 do Zeraora e 71 do Meowth), em ordem de lançamento
- Visual de fichário com duas páginas lado a lado no computador e uma página 2x2 no celular
- Marcação das cartas que você já tem, com progresso por coleção
- Filtros (Todas, Faltando, Tenho), busca por nome ou coleção e atalho para pular até uma coleção
- Geração de PDF A4 com as cartas que faltam, em tamanho real, para imprimir e colocar no lugar
- Link de cada carta para a página dela na LigaPokémon
- Tema claro e escuro automático
- Progresso salvo no próprio navegador (localStorage)

## Tecnologias

- HTML, CSS e JavaScript puro, em um único arquivo, sem framework e sem build
- [jsPDF](https://github.com/parallax/jsPDF) para gerar o PDF
- Imagens das cartas carregadas da API pública [TCGdex](https://tcgdex.dev). Quando uma imagem não existe, o bolso mostra o nome e o número da carta.

## Como rodar

Abra o `index.html` no navegador. Não precisa instalar nada.

## Fontes dos dados

A lista de cartas foi conferida com Bulbapedia, pkmncards, Limitless e TCGdex. As versões em português foram confirmadas no banco de dados oficial (pokemon.com/br) e em ofertas na LigaPokémon.

---

Projeto pessoal de fã, sem fins comerciais e sem relação com The Pokémon Company, Nintendo, Game Freak ou Copag. Pokémon e os nomes das cartas são marcas de seus respectivos donos.
