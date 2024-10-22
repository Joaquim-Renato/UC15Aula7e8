Links uteis: 

GRID: A simple visual cheatsheet for CSS Grid Layout:
https://grid.malven.co/


FLEX: A simple visual cheatsheet for flexbox:
https://flexbox.malven.co/

Favicons: 
https://www.favicon.cc/?action=icon&file_id=926317


**gap: 10px** -> Espaçamento entre elementos

# Display Grid:

As linhas verticais dos itens da grade são chamadas de 
colunas - *columns*

**grid-template-columns**

As linhas horizontais dos itens da 
grade são chamadas de linhas – *rows*

**grid-template-rows**

**grid-template-columns** - Defini o total de colunas e o tamanho de cada uma;

**grid-template-rows** - Define o total de linhas e o tamanho de cada uma;

**fr** - Unidade fracionária que terá como objetivo distribuir o espaço da grid;

**gap** - Cria uma distância entre os elementos do grid, tanto horizontal quanto vertical (gap=lacuna);

**row-gap: 10px ;** ajusta distância entre linhas;

**column-gap: 10px** ; ajusta distância entre colunas;
---

# Layout de Grid com CSS

Este projeto demonstra o uso do layout `grid` no CSS para criar uma página web com três colunas e três linhas, com alturas e espaçamentos personalizados.

## Estrutura do CSS

Abaixo está uma explicação de cada linha do código CSS utilizado:

```css
/* Define o container como um grid */
display: grid;

/* Cria 3 colunas de largura igual usando a fração do espaço disponível (1fr) */
grid-template-columns: repeat(3, 1fr);

/* Define 3 linhas com alturas específicas: 200px, 100px, e 150px */
grid-template-rows: 200px 100px 150px;

/* Define um espaçamento de 10px entre as colunas e as linhas do grid */
gap: 10px;

/* Adiciona um preenchimento interno de 10px ao redor do container */
padding: 10px;

```
