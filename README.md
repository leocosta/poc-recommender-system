# Sistema de Recomendação de Aplicativos


## Coleta dos Dados

- Fonte dos dados
- Demonstração dos dados em estado bruto
- Dados relevantes para o SR
    - Terminal
    - ApplicationId
    - View
    - Installation

## Processamento dos Dados

- Extração de logs de Visualização
- Extração de logs de Instalação
- Identificação de registros repetidos
- Remoção de registros repetidos
- Junção dos dados de Visualização/Instalação e Cálculo do Score
- Prévia dos dados processados


## Exploração e Análise dos Dados

- Visualização e Instalação
    - Análise de Visualizações
    - Análise de Instalações
- Terminais que interagiram com os aplicativos
    - Análise dos dados
    - Gráfico de distribuição
    - Gráfico de dispersão
- Popularidade dos aplicativos
    - Análise dos dados
    - Gráfico de distribuição
    - Gráfico de dispersão


## Modelos de Machine Learning

- Carregamento dos dados de treino e teste
- Criação das matrizes de treino e teste
- Métodos de recomendação
    - Most-Popular
    - Best-Rated
    - PureSVD

## Avaliação dos Resultados

- Carregamento dos dados de teste
- Resultado da avaliação *Hit-Rate*
    - *Min, max, average, median* and *std* da avaliação *Hit-Rate*
    - Gráficos da avaliação *Hit-Rate*
- Resultado da avaliação *Precision and Recall*
    - *Min, max, average, median* and *std* da avaliação *Precision and Recall*
    - Gráficos da avaliação *Precision and Recall*
- Resultado da avaliação *Reciprocal Rank*  
    - *Min, max, average, median* and *std* da avaliação *Reciprocal Rank*
    - Gráficos da avaliação *Reciprocal Rank*
