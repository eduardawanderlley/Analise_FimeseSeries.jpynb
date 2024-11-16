# Análise de Dados de Filmes e Séries
Este projeto é uma análise exploratória de dados de um conjunto de filmes, com o objetivo de descobrir padrões, tendências e insights sobre a indústria cinematográfica. Utilizando Python e bibliotecas de análise de dados, como Pandas, Matplotlib e Seaborn, o projeto apresenta visualizações e métricas que ajudam a responder perguntas importantes sobre gêneros, avaliações e lançamentos ao longo do tempo.

# Objetivo
* Explorar e analisar os dados de filmes e séries para extrair informações úteis e identificar padrões significativos.
* Criar visualizações que ajudem a comunicar insights de forma clara e visualmente atraente.
* Demonstrar habilidades práticas em manipulação de dados, análise exploratória e visualização.

# Perguntas Respondidas
* Quais são os gêneros mais populares?
* Como as avaliações médias variam por gênero?
* Quais são os anos com maior quantidade de lançamentos?
* Quais filmes têm as melhores e piores avaliações?
* Existe relação entre o orçamento e a avaliação de um filme?

# Tecnologias Utilizadas
Python: Linguagem de programação principal do projeto.

# Bibliotecas:
* Pandas: Para manipulação e análise dos dados.
* Seaborn e Matplotlib: Para criação de gráficos e visualizações.

# Etapas do Projeto
## 1. Carregamento dos Dados
* O dataset é carregado diretamente no ambiente utilizando Pandas.
* A estrutura dos dados foi inspecionada com métodos como .head(), .info() e .isnull().sum() para entender a distribuição e identificar valores ausentes.
## 2. Limpeza de Dados
* Valores ausentes foram tratados, e os gêneros foram padronizados para facilitar a análise.
* Novas colunas, como décadas de lançamento, foram criadas para enriquecer o conjunto de dados.
## 3. Análise Exploratória
* Foram calculadas métricas como:
* Quantidade de filmes por gênero e por ano.
* Média de avaliação por gênero.
* Identificação dos 10 melhores e piores filmes, baseando-se nas avaliações.
## 4. Visualizações

# Gráficos foram criados para comunicar os insights de maneira visual:
* Gráfico de barras: Mostrando os 10 gêneros mais populares.
* Gráfico de linha: Exibindo a evolução do número de lançamentos ao longo dos anos.
* Gráfico de dispersão: Analisando a relação entre orçamento e avaliação, com diferenciação por gênero.

# Principais Insights
* O gênero mais popular e seu domínio em número de produções.
* A tendência de lançamentos ao longo das décadas, identificando períodos de maior atividade cinematográfica.
* A relação (ou ausência de relação) entre orçamento e avaliação, além das diferenças por gênero.
* Os melhores e piores filmes segundo as avaliações.
