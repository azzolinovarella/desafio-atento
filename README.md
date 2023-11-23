# Desafio Atento

Este repositório contém os arquivos utilizados para o desenvolvimento do desafio da Atento desenvolvido como uma etapa do processo seletivo da empresa.

---

## Objetivo
O objetivo deste desafio é avaliar as habilidades de um consultor de Data Science para avaliar as capacidades de realizar análises técnicas e resolução de problemas.

## Descrição do desafio
- Seu cliente é uma plataforma hub de restaurante. Essa plataforma possui uma função de avaliação dos restaurantes com comentários.

- Seu trabalho é auxiliar nas estratégias de melhoria de satisfação dos clientes a fim de melhoria do serviço dos restaurantes conveniados.

- Você deve criar um algoritmo de classificação por meio de análise de sentimentos que será alocado no cliente para reduzir custos de infraestrutura.

- O cliente te disponibilizou apenas uma base de comentários das avaliações dos clientes que frequentaram os restaurantes.

## Instruções
1. Utilize python para desenvolver a análise

2. Crie o target de sentimentos dos comentários via contexto por meio de algoritmo de LLM*

3. Crie um algoritmo para classificação dos comentários por análise de sentimento*

4. Analise os comentários de acordo com a classificação com modelagem de tópicos

5. Utilize o algoritmo de classificação para predição da base valid.csv

*Base de comentários: dataset_train.csv

## Entrega
1. Código com o desenvolvimento da análise e algoritmo utilizado de acordo com as instruções

2. Predição da base de comentários “dataset_valid.csv” com ‘target’ de análise sentimento

## Critérios que serão avaliados
1. Capacidade de entendimento do problema.

2. Capacidade analítica.

3. Conhecimento de frameworks.

4. Conhecimento de metodologias de tratamento e análise de dados.

5. Qualidade do código.

6. Explicação da solução.

7. Resultado da classificação.

8. Apresentação dos resultados.

---
## ToDo

[X] Usar algum modelo da HuggingFace (e.g. [bertweet-base-sentiment-analysis](https://huggingface.co/finiteautomata/bertweet-base-sentiment-analysis) que aborde [análise de sentimentos via texto](https://huggingface.co/blog/sentiment-analysis-python)  para estimar a variável target da base de treino
[ ] A partir da nova base de dados gerada (com targets), criar um algoritmo de classificação.
[ ] Usar algum modelo da HuggingFace (e.g. ) que aborda [modelagem de tópicos](https://huggingface.co/blog/bertopic) para analisar os comentários.
[ ] Utilizar o algoritmo de classificação na base de validação.
[ ] (OPT) Criar uma API em Flask que recebe o texto e traz a classe
[ ] (OPT) Criar um APP com Streamlit para mostrar os resultados de forma mais visual
[ ] (OPT) Encapsular tudo em Docker.
