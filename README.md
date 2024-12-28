# NLP Review Products
Projeto de NLP para o módulo de Deep Learning UFPE


## Introdução
Esse projeto tem como objetivo utilizar modelos de inteligência artificial (NLP) para automatizar e classificar os reviews de usuários em scores de 1 a 5.

A Olist é uma startup brasileira que atua no segmento de tecnologia para varejo. A empresa fornece soluções que facilitam a gestão de lojas off-line e online (e-commerce). A Olist concentra vendedores que desejam anunciar em marketplaces como Mercado Livre, Americanas e Amazon, de tal forma que os produtos de todos os vendedores ficam em uma loja única visível ao consumidor final. A empresa possui mais de 30 mil lojistas cadastrados, além de 2 milhões de consumidores únicos a cada ano. ([Wikipédia](https://pt.wikipedia.org/wiki/Olist))

Para esse projeto foi utilizado a base de dados aberta da Olist de avaliações e reviews de produtos comercializados, podendo ser encontrada no [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_items_dataset.csv). 

Para a avaliação de reviews foi escolhido os produtos de Telefonia, no qual resultou em uma amostra com 2050 reviews de produtos de Telefonia.

## Base de dados

Base de dados da Olist de avaliações e reviews de produtos comercializados, encontrada no [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_items_dataset.csv). 

## Modelos utilizados
- SVM + BoW
- SVM + TFIDF
- SVM + Word2Vector CBOW 300
- SVM + Word2Vector SKIP-GRAM 300
- BERT (BERTimbau)
- LLM GTP-4 Mini

## Estrutura do projeto

- data : base de dados do projeto
- notebooks : notebooks para análise exploratória e modelagem do problema
- src : código fonte python extraido dos notebooks
- apresentacao : slides de apresentação

## Instalação e uso
Para instalação e uso utilizar o Google Colab.

obs: Para rodar os Notebooks e códigos fontes desse projeto, as variavéis **OPENAI_API_KEY** e **PROJECT_PATH** devem ser colocadas em secrets no Google Colab.

```
OPENAI_API_KEY = "API Secret da OpenAI"
PROJECT_PATH = "Root Path do projeto no Google Drive"
```

## Apresentação

Os slides da apresentação podem ser encontrados na pasta ```apresentacao```.

O video de apresentação pode ser visto pelo link [https://youtu.be/CxIlBiSyROQ](https://youtu.be/CxIlBiSyROQ)


## Autor
Os notebooks encontrados nesse repositório foram desenvolvidos por Lucas Accioly para o projeto final do módulo de NLP da especialização em Deep Learning da Universidade Federal de Pernambuco (UFPE).


Autor: Lucas Accioly
