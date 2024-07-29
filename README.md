# Análise de Tweets da Conferência Nintendo - Python

- [Versão em Português](#versão-em-português)
- [English Version](#english-version)

## Versão em Português

Bem-vindo ao projeto de Análise de Tweets da Conferência Nintendo! Este projeto realiza uma análise detalhada de mais de 4000 tweets sobre a conferência da Nintendo utilizando várias bibliotecas do Python e técnicas de processamento de linguagem natural (NLP).

Json adquirido em: https://www.kaggle.com/datasets/xvivancos/tweets-during-nintendo-e3-2018-conference

### Funcionalidades

1. **Identificação das 10 Entidades Mais Relevantes**: Utilizamos um algoritmo para extrair e identificar as 10 entidades mais relevantes dentro de mais de 4000 tweets.
2. **Alocação das Entidades em Arrays**: As entidades identificadas são alocadas em um array específico para facilitar a análise subsequente.
3. **Extração de Tweets por Entidade**: Para cada entidade, extraímos todos os tweets que a mencionam e alocamos em arrays separados.
4. **Análise de Sentimentos**: Usamos a biblioteca nltk.sentiment.vader para calcular os valores de sentimento de cada palavra nos tweets alocados nos arrays específicos de suas entidades.
5. **Visualização de Sentimentos**: Os valores de sentimentos calculados são exibidos em forma de gráfico para uma melhor compreensão.

### Outras Funcionalidades

- **Verbos Mais Utilizados**: Extração e exibição dos verbos mais frequentemente usados nos tweets.
- **Nuvem de Palavras**: Criação de uma nuvem de palavras para mostrar as palavras mais comentadas durante a conferência da Nintendo.
- **Sentimento Mais Relevante por Minuto**: Análise do sentimento mais relevante em cada minuto da conferência.
- **Palavras Mais Comentadas por Minuto**: Listagem das 10 palavras mais comentadas em cada minuto.

## English Version

Welcome to the Nintendo Conference Tweet Analysis project! This project performs a detailed analysis of more than 4000 tweets about the Nintendo conference using various Python libraries and natural language processing (NLP) techniques.

Json acquired from: https://www.kaggle.com/datasets/xvivancos/tweets-during-nintendo-e3-2018-conference

## Features

1. **Identification of the Top 10 Relevant Entities**: We use an algorithm to extract and identify the top 10 relevant entities from more than 4000 tweets.
2. **Allocating Entities into Arrays**: The identified entities are allocated into a specific array for subsequent analysis.
3. **Extracting Tweets by Entity**: For each entity, we extract all tweets that mention it and allocate them into separate arrays.
4. **Sentiment Analysis**: We use the nltk.sentiment.vader library to calculate the sentiment values of each word in the tweets allocated in the specific arrays of their entities.
5. **Sentiment Visualization**: The calculated sentiment values are displayed in the form of a graph for better understanding.

### Other Features

- **Most Used Verbs**: Extraction and display of the most frequently used verbs in the tweets.
- **Word Cloud**: Creation of a word cloud to show the most commented words during the Nintendo conference.
- **Most Relevant Sentiment per Minute**: Analysis of the most relevant sentiment for each minute of the conference.
- **Most Commented Words per Minute**: Listing of the top 10 most commented words per minute.
