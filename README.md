# Engajamento-Instagram
Análise de dados Com Python
Análise de Engajamento no Instagram
Este repositório contém uma análise dos dados de engajamento no Instagram para entender quais tipos de conteúdo geram mais interação. A análise foi realizada usando dados históricos das postagens no Instagram desde o início das publicações até o dia 27 de março.

Objetivo
O objetivo desta análise é responder às seguintes perguntas:

Qual tipo de conteúdo mais engaja no Instagram da minha empresa?

Quais campanhas geraram mais interações?

Direcionamentos para a Análise:
Campos ignorados: Visualizações, pois o foco da análise é em curtidas, comentários e interações.

Tratamento de tags: Tags vazias foram tratadas como valores ausentes.

Estrutura dos Dados
A base de dados contém as seguintes colunas:

Tipo: Tipo do conteúdo publicado (Foto, Vídeo, Carrossel, etc.).

Data: Data de publicação.

Curtidas: Número de curtidas recebidas.

Comentários: Número de comentários recebidos.

Visualizações: Número de visualizações (ignorado na análise).

Tags: Tags associadas à publicação.

Pessoas: Responsável pela postagem.

Campanhas: Campanha à qual a postagem pertence.

Carrossel: Indica se o post é um carrossel (S ou N).

Interações: Total de interações (curtidas + comentários).

Etapas da Análise
Importação dos dados: Os dados foram carregados a partir de um arquivo Excel.

Limpeza de dados: A análise tratou valores ausentes e dados inconsistentes, como valores nulos nas colunas de tags.

Exploração dos dados: Foram realizadas verificações nos tipos de dados e contagem de valores nulos.

Visualizações: A análise incluiu gráficos de barras e linhas para explorar as médias de curtidas e comentários por pessoa e campanha.

Gráficos Gerados
A análise gerou os seguintes gráficos para visualização:

Gráfico de barras: Para mostrar a média de curtidas e comentários por pessoa e campanha.

Gráfico de linhas: Para observar a evolução do engajamento ao longo do tempo.

Conclusão
Esta análise ajuda a entender quais tipos de postagens e campanhas geram mais interações, permitindo tomar decisões mais informadas sobre as estratégias de marketing no Instagram.
