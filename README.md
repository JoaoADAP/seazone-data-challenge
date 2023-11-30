# Seazone Data Challenge

## Descrição do Projeto

Este projeto consiste na análise das bases de dados fornecidas pela Seazone, detalhes.csv e rating.csv, como parte do desafio proposto pela empresa. O objetivo é demonstrar habilidades analíticas, interpretativas e de visualização de dados ao responder a diversas questões relacionadas aos anúncios de hospedagem.

## Tecnologias Utilizadas

- Linguagem de Programação: Python
- Ferramenta de Análise: Jupyter Notebook
- Bibliotecas Python: Pandas, NumPy, Matplotlib, Seaborn, Geopy

## Dados

Os dados utilizados neste projeto foram extraídos de dois arquivos CSV fornecidos pela Seazone:

- `desafio_details.csv`: Contém características de cada imóvel/anúncio.
- `desafio_rating.csv`: Contém dados sobre as avaliações dos imóveis.

## Como Rodar o Código

- Tenha o Python instalado e abra seu notebook Jupyter
- Pegue o código de seazone-data-challenge.ipynb
- Certifica-se se todas as bibliotecas utilizadas no código estão instaladas

## Resultados

Para uma análise mais aprofundada e a visualização completa dos resultados, confira o [PDF do Relatório Completo](https://drive.google.com/file/d/1_fQ44yz6vP1U9Hk3Dc0wXY7keTgc28wX/view?usp=sharing).

### 1. Ordenação das Cidades por Número de Listings

- Florianópolis: 762 Listings
- Goiânia: 138 Listings
- Bombinhas: 65 Listings
- Ubatuba: 35 Listings
- Balneário Camboriú: 35 Listings

### 2. Ordenação das Cidades por Metros Quadrados

A cidade de Trancoso possui a maior média de metros quadrados por apartamento, totalizando 192 m².

### 3. Cidades com Mais Avaliações

As 10 cidades com mais avaliações, lideradas por Florianópolis, que apresenta um número significativamente maior de avaliações devido ao maior número de listings.

### 4. Cidades com a Maior e Menor Média de Avaliações

Angra dos Reis obteve a maior média, embora baseada em apenas uma avaliação. Florianópolis teve uma média de 9,1 com base em 87.353 avaliações.

### 5. Correlações entre Características do Anúncio e Localização

Observou-se uma relação moderada entre a localização e as categorias de "Comodidades", "Limpeza", "Conforto", "Custo-benefício" e "Total".

### 6. Relações entre Nota do Anúncio e Recursos Disponíveis

Não foi encontrada uma relação significativa entre a nota total e os recursos individuais.

### 7. Relação entre Nota Recebida e Localização

Observou-se uma correlação de 0.49 entre a nota total e a localização, indicando uma influência moderada.

### 8. Inferências sobre as Notas dos Imóveis

As notas têm uma forte correlação com as comodidades, limpeza, conforto e custo-benefício. A localização tem uma correlação média. As avaliações tendem a ser consistentemente elevadas.

### 9. Anúncios Críticos

Anúncios com pontuações extremamente baixas (0-4) indicam insatisfação significativa dos usuários em várias áreas.

### 10. Possíveis Análises Futuras

Análises futuras podem incluir correlações entre cidade e outros valores, relações entre o tipo de acomodação e o restante do anúncio, entre outros.

### 11. Design do Dashboard

Um dashboard simplificado, apresentando um mapa de calor abrangendo todas as informações, gráficos de número de listings e nota média, seria ideal para uma visão geral rápida.

### 12. Dados Adicionais

Informações adicionais que poderiam enriquecer a análise incluem preço do aluguel, políticas de cancelamento, clima local, tipo de tomada e acessibilidade.

### 13. Melhoria das Notas

Melhorias nas notas podem ser alcançadas investindo em comodidades, melhorando a limpeza e conforto, e considerando adições ou inovações para enriquecer a experiência dos hóspedes.

