# Modelo de predição de preços

Diante mão afirmo que nem todas as entregas exigidas na documentação deste desafio foram cumpridas.

Entregas - 

Visualize um resumo do que foi entregue neste projeto:

Os itens serão marcados com V ou X.

feito (v)  Incompleto(X)

**Análise Exploratória:** (v) 

**Questões de Negócio:**(v)

 1- Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?

 2- O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?

 3- Existe algum padrão no texto do nome do local para lugares de mais alto valor

**Modelo Preditivo** (X)

## Documentação do Projeto

Este projeto tem como objetivo desenvolver um modelo de previsão de preços com base em um dataset de anuncios airbnb. Durante o projéto ja foram realizadas:

1- Análise Exploratória  
2- Análise Descritiva  
3- Pré-Processamento  
4- Hipoteses de Negócio

Os seguintes processos estão documentados no arquivo Analise_Exploratoria_EDA.ipynb

## Replicação das Análises

A critério de Replicação, o dataset utilizado no projéto estar localizado no diretório dados. As instruções do desafio estarão localizadas no diretório descrição do projeto.

Para realizar a replicação do projeto, basta clonar o repositório ou baixar o arquivo do notebook juntamente aos dados, e abrilos através do navegador ou Anaconda. 

## Sobre os Dados

O dataset possui um total de 48894 registros com as seguintes colunas:

- id: Identificação única para cada anúncio (int64)
- nome: Nome da hospedagem (object)
- host_id: Identificação do usuário que hospedou o anúncio (int64)
- host_name: Nome do usuário que hospedou o anúncio (object)
- bairro_group: Nome do bairro onde o anúncio está localizado (object)
- bairro: Nome da área onde o anúncio está localizado (object)
- latitude: Latitude do local (float64)
- longitude: Longitude do local (float64)
- room_type: Tipo de espaço de cada anúncio (object)
- price: Preço por noite em dólares listado pelo anfitrião (int64)
- minimo_noites: Número mínimo de noites que o usuário deve reservar (int64)
- numero_de_reviews: Número de comentários dados a cada listagem (int64)
- ultima_review: Data da última revisão dada à listagem (object)
- reviews_por_mes: Número de avaliações fornecidas por mês (float64)
- calculado_host_listings_count: Quantidade de listagem por host (int64)
- disponibilidade_365: Número de dias em que o anúncio está disponível para reserva (int64)


