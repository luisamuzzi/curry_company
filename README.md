# Projeto de análise de dados da empresa Curry Company

### Resumo

Este projeto foi desenvolvido como parte do curso de Python da Comunidade DS para estudo da linguagem python voltada à análise de dados e do framework streamlit.

[Acesse aqui o dashboard](https://lm-curry-company.streamlit.app/).

### Índice

* [1. Problema de negócio](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#1-problema-de-neg%C3%B3cio)
* [2. Premissas assumidas para a análise](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#2-premissas-assumidas-para-a-an%C3%A1lise)
* [3. Estratégias da solução](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#3-estrat%C3%A9gias-da-solu%C3%A7%C3%A3o)
* [4. Top 3 Insights de dados](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#4-top-3-insights-de-dados)
* [5. O produto final do projeto](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#5-o-produto-final-do-projeto)
* [6. Conclusão](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#6-conclus%C3%A3o)
* [7. Próximos passos](https://github.com/luisamuzzi/curry_company?tab=readme-ov-file#7-pr%C3%B3ximos-passos)

### 1. Problema de negócio

A Cury Company é uma empresa de tecnologia que criou um aplicativo que conecta restaurantes, entregadores e pessoas. Através desse aplicativo, é possível realizar o pedido de uma refeição, em qualquer restaurante cadastrado, e recebê-lo no conforto da sua casa por um entregador também cadastrado no aplicativo da Cury Company.

A empresa realiza negócios entre restaurantes, entregadores e pessoas, e gera muitos dados sobre entregas, tipos de pedidos, condições climáticas, avaliação dos entregadores, etc. A Cury Company possui um modelo de negócio Marketplace, que faz o intermédio do negócio entre três clientes principais: restaurantes, entregadores e pessoas compradoras. Para acompanhar o crescimento desses negócios, analisou-se:

#### Do lado da empresa:

1. Quantidade de pedidos por dia.
2. Quantidade de pedidos por semana.
3. Distribuição dos pedidos por tipo de tráfego.
4. Comparação do volume de pedidos por cidade e tipo de tráfego.
5. A quantidade de pedidos por entregador por semana.
6. A localização central de cada cidade por tipo de tráfego.

#### Do lado do entregador:

1. A menor e maior idade dos entregadores.
2. A pior e a melhor condição de veículos.
3. A avaliação médida por entregador.
4. A avaliação média e o desvio padrão por tipo de tráfego.
5. A avaliação média e o desvio padrão por condições climáticas.
6. Os 10 entregadores mais rápidos por cidade.
7. Os 10 entregadores mais lentos por cidade.

#### Do lado dos restaurantes:

1. A quantidade de entregadores únicos.
2. A distância média dos resturantes e dos locais de entrega.
3. O tempo médio e o desvio padrão de entrega por cidade.
4. O tempo médio e o desvio padrão de entrega por cidade e tipo de pedido.
5. O tempo médio e o desvio padrão de entrega por cidade e tipo de tráfego.
6. O tempo médio de entrega durantes os Festivais.

O objetivo desse projeto é criar um conjunto de gráficos e/ou tabelas que exibam essas métricas.

### 2. Premissas assumidas para a análise

1. A análise foi realizada com dados entre 11/02/2022 e 06/04/2022.
2. Marketplace foi o modelo de negócio assumido.
3. Os 3 principais visões do negócio foram: Visão transação de pedidos, visão restaurante e visão entregadores.
4. Fonte dos dados: 

### 3. Estratégias da solução

O painel estratégico foi desenvolvido utilizando as métricas que refletem as 3 principais visões do modelo de negócio da empresa:

1. Visão do crescimento da empresa
2. Visão do crescimento dos restaurantes
3. Visão do crescimento dos entregadores

Cada visão é representada pelo seguinte conjunto de métricas:

1. Visão do crescimento da empresa
    
    a. Pedidos por dia
    
    b. Porcentagem de pedidos por condições de trânsito
    
    c. Quantidade de pedidos por tipo e por cidade.
    
    d. Pedidos por semana
    
    e. Quantidade de pedidos por tipo de entrega
    
    f. Quantidade de pedidos por condições de trânsito e tipo de cidade
    
2. Visão do crescimento dos restaurantes
    1. Quantidade de pedidos únicos.
    2. Distância média percorrida.
    3. Tempo médio de entrega durante festival e dias normais.
    4. Desvio padrão do tempo de entrega durante festivais e dias normais.
    5. Tempo de entrega médio por cidade.
    6. Distribuição do tempo médio de entrega por cidade.
    7. Tempo médio de entrega por tipo de pedido.

3. Visão do crescimento dos entregadores
    1. Idade do entregador mais velho e do mais novo.
    2. Avaliação do melhor e do pior veículo.
    3. Avaliação média por entregador.
    4. Avaliação média por condições de trânsito.
    5. Avaliação média por condições climáticas.
    6. Tempo médio do entregador mais rápido.
    7. Tempo médio do entregador mais rápido por cidade.

### 4. Top 3 Insights de dados

1. A sazonalidade da quantidade de pedidos é diária. Há uma variação de aproximadamente 10% do número de pedidos em dia sequenciais.
2. As cidades do tipo Semi-Urban não possuem condições baixas de trânsito.
3. As maiores variações no tempo de entrega, acontecem durante o clima ensolarado.

### 5. O produto final do projeto

Painel online, hospedado em um Cloud e disponível para acesso em qualquer dispositivo conectado à internet.

O painel pode ser acessado através desse link: https://lm-curry-company.streamlit.app/

### 6. Conclusão

O objetivo desse projeto é criar um conjunto de gráficos e/ou tabelas que exibam essas métricas da melhor forma possível para o CEO.

Da visão da Empresa, podemos concluir que o número de pedidos
cresceu entre a semana 06 e a semana 13 do ano de 2022.

### 7. Próximos passos

1. Reduzir o número de métricas.
2. Criar novos filtros.
3. Adicionar novas visões de negócio.
