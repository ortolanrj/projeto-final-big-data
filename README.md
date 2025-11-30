# Projeto Final - Gerenciamento de Dados em Larga Escala
Projeto Final da disciplina de Gerenciamento de Dados em Larga Escala

## Problema abordado

Decidimos abordar o domínio de vendas de jogos para este Projeto Final. Vimos que este assunto permitiria uma pluralidade de análises
e insights diferentes, devido ao tamanho da série histórica de jogos ao longo dos anos.

#### Dataset utilizado neste projeto: https://www.kaggle.com/code/upadorprofzs/eda-video-game-sales/

## Ferramentas utilizadas

Foram utilizadas 4 principais ferramentas para a execução deste trabalho:
- Apache Spark (PySpark)
- Pandas
- Matplotlib
- Streamlit

Apache Spark foi utilizado pela natureza dos dados, considerando um dataset com um contexto e volume coerentes para Big Data.

Pandas foi utilizaado para o tratamento e manipulação dos datasets. Se mostrou uma ótima ferraamenta para manipular a estrutura do dataset,
mudar posição de colunas, adicionar aliases às colunas quando necessário, etc.

Matplotlib foi a biblioteca essencial para a criação das visualizações e gráficos presentes no trabalho. Conseguimos fazer visualizações que retratassem
de forma intuitiva os insights que acreditamos ser importantes, baseados no dataset.

Utilizamos o Streamlit como uma forma mais prática e simples de mostrar os gráficos presentes no trabalho, não dependendo de um notebook para isto.

## Visualizações geradas

As visualizações abordadas foram as seguintes:

### Vendas por região ao longo dos anos

Achamos interessante apresentar o aspecto quantitativo das vendas feitas por cada região, tendo noção sobre quais regiões tem mais vendas de jogos em relação à outras.

<img width="1164" height="707" alt="image" src="https://github.com/user-attachments/assets/0ad4d385-014d-4234-8404-dc7b82d045d1" />

### Vendas Globais por Publisher ao longo dos anos (Top 5)

Neste caso, queríamos ter ideia de quais publisher tinham mais vendas. Decidimos reduzir o escopo para as 5 maiores, pois a quantidade de publishers presentes no dataset, é muito grande,
ficando muito complicada à visualização de todas pela forma que gostaríamos de apresentar os dados.

<img width="1164" height="707" alt="image" src="https://github.com/user-attachments/assets/5667106f-6a5e-4719-aeef-bcdf16f518c4" />

### Jogo mais vendido por Plataforma (Vendas Globais)

Aqui decidimos fazer um layout um pouco diferente, com um gráfico em barras. O objetivo foi mostrar os jogos mais vendidos em cada plataforma. Foi possível fazer a ordenação decrescente dos dados,
juntamente com um heatmap, deixando bem evidente qual jogo mais vendido, podendo olhar diretamente à qual plataforma tal jogo pertence.

<img width="1389" height="789" alt="image" src="https://github.com/user-attachments/assets/31986246-93f9-4cba-86d8-b90022ac8a2a" />

### Publisher com mais vendas por Plataforma (Vendas Globais)

Neste caso, decidimos fazer algo semelhante ao gráfico anterior, porém pensando desta vez com o Publisher com mais vendas. Fica bem evidente assim, quem é a Publisher com o maior número histórico de vendas.
Deixando claro também, qual plataforma que o maior número de vendas da Publisher se refere.

<img width="1390" height="789" alt="image" src="https://github.com/user-attachments/assets/f6040f58-3277-4ce2-bcbc-d5b88b457d0a" />
