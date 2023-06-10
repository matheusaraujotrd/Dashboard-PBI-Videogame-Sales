# Dashboard-PBI-Videogame-Sales

Dashboard montada no Power BI sobre um conjunto de dados de venda de jogos digitais.

## Sobre o conjunto de dados
O conjunto de dados foi criado originalmente por Ulrik Thyge Pedersen e está disponibilizado no Kaggle (https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales)

O tratamento dos dados foi feito anteriormente em outro repositório e o relatório Jupyter está incluso
apenas para motivos de documentação.

## Sobre o Dashboard

Não é o Dashboard mais bonito do mundo, mas é bem funcional. Ele contém os valores das vendas globais
de praticamente todos os principais fabricantes relevantes de jogos digitais. É possível interagir com os
gráficos e obter os gêneros mais comprados e os jogos mais comprados de cada fabricante, sejam no registro
histórico geral ou em cada ano de vendas. Também é possível relacionar as vendas dos portáteis. O PDF
Game Sales Sample mostra um exemplo visual do Dashboard.

O Dashboard "Model 2" inclui um gráfico de barras empilhadas no lugar do gráfico de linhas, onde consta
a média móvel das vendas anuais.

De modo geral, os dashboards incluem:

### Visão Geral

* Vendas Totais: vendas de jogos por fabricante (isto é, contabilizando todos os consoles fabricados por empresa x) em todo o mundo.
* Vendas Totais por Portátil: Venda de jogos em todo o mundo considerando apenas consoles portáteis.
* Cards informativos: Informação sobre os jogos mais vendidos de cada região, seja geral, por fabricante ou por portátil.

Todos os dados são interativos entre si. É possível selecionar fabricante x para visualizar os portáteis referentes a ele e vice-versa. Ao selecionar uma empresa ou portátil específico, também é possível ver os jogos mais vendidos de cada região.

### Vendas Anuais

* Vendas Totais: Um gráfico que representa a variação ano a ano dos dados das vendas de jogos. Uma versão mais "detalhada" do que a presente na Visão Geral.
* Top 5 Gêneros (Total): Classificação dos gêneros mais vendidos, seja total, por fabricante de console, ou por ano e fabricante.
* Filtro: O filtro na barra superior permite escolher para quais fabricantes visualizar as informações, atualizando todas visualizações da página.
* Card informativo: Um cartão informativo com o jogo mais vendido, seja total, seja em determinado gênero, ou seja por ano, gênero e fabricante.

Matheus Alexandre de Araujo, 08/06/23
matheusalexandre.engcomp@gmail.com

