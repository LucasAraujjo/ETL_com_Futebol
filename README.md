# ETL com futebol
Este repositório abriga um projeto de ETL (Extração, Transformação e Carga) e análise de dados voltado para estatísticas e informações sobre competições europeias de futebol. Utilizando ferramentas como Pandas para manipulação de dados e Power BI para visualização, o projeto visa extrair dados de uma base pública, transformá-los em insights acionáveis e apresentá-los de forma intuitiva. Explore as tendências, resultados e desempenho de jogadores ao longo das competições europeias mais renomadas, tudo isso disponível para análise.

## Objetivo
O objetivo deste projeto é extrair dados de uma base de dados pública sobre competições europeias de futebol, realizar transformações necessárias para preparar os dados para análise, carregar os dados em um formato adequado e, finalmente, realizar análises exploratórias utilizando o Power BI.

## Fonte de Dados
Os dados são extraídos de uma base de dados pública elaborada em diversos arquivos .csv, obtida no site Kaggle, sobre estatísticas e informações de jogadores profissionais de futebol que atuaram em competições europeias. A base de dados pode ser encontrada aqui: https://www.kaggle.com/datasets/davidcariboo/player-scores \
Não foi possível colocar os arquivos do dataset utilizados dentro do repositório devido aos seus tamanhos serem grandes demais, mas os resultados do script de manipulação de dados podem ser vistos normalmente no repositório.

## Estrutura do Repositório
**dashboard:** Pasta que contém o arquivo do dashboard Power Bi e a imagem de sua tela de fundo. \
**complete_data.csv:** Contém os dados tratados carregados em um arquivo csv. \
**complete_data.xlsx:** Contém os dados tratados carregados em um arquivo excel. \
**players.ipynb:** Contém os scripts Python para extração, transformação e carregamento de dados. \
**README.md:** Este arquivo, fornecendo uma visão geral do projeto e instruções de uso. \

## Visualização de Dados

Após todo o processo de transformação dos dados, o Power Bi é utilizado como ferramenta principal para visualização de dados. Exportando os dados tratados para um arquivo excel, foi possível desenvolver um dashboard para visualização dos dados, permitindo uma análise exploratória mais objetiva e com alguns insights relevantes a partir desses dados. O Power Bi pode ser encontrado nesse link: https://app.powerbi.com/view?r=eyJrIjoiMDFlOWVlZGEtNzdjZC00YjFlLWFkNGUtMWQzYjE1YWI2ZmJkIiwidCI6ImRkYWFmYTA0LWI4YjctNDQzMC04N2QxLThkZjY1NDZjNGQ5NSJ9
