# Desafio Atento

Este repositório contém os arquivos utilizados para o desenvolvimento do desafio da Atento desenvolvido como uma etapa do processo seletivo da empresa.

## Instruções de execução

Para este desafio, dividiu-se os processo em 3 notebooks (todos disponíveis no repositório `notebooks`): 

- `01-DataPreProcessing.ipynb`: Contém a etapa de pré-processamento dos dados e inferência dos targets por meio de um LLM (usado posteriormente para o treinamento de um outro modelo).
- `02-ModelTraining.ipynb`: Contém a etapa de treinamento e seleção de um modelo de análise de sentimento a partir dos targets inferidos no notebook anterior.
- `03-ValidationDataAnalysis.ipynb`: Contém a etapa da inferência dos sentimentos na base de validação e a modelagem de tópicos desta mesma base.

Em cada um dos notebooks citados acima encontram-se, além do código, todo o processo comentado e documentado.

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

