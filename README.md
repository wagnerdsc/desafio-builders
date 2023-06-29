# desafio-builders
# Dashboard de Inteligência de Dados - Desafio de Vaga para Analista de Dados Sênior

## Link para o Dashboard
https://lookerstudio.google.com/reporting/03d267b5-9505-4813-b94d-57107879a1be

O dashboard foi criado utilizando a ferramenta LookerStudio para visualização de dados e foi desenvolvido um processo de ETL utilizando Python. Foram gerados 8 arquivos CSV durante o processo de ETL, sendo 6 dimensões e 2 fatos.

## Dados

Os dados utilizados foram divididos em duas categorias: multas de trânsito e dados relacionados à Covid-19. O processo de ETL foi realizado utilizando Python para extrair, transformar e carregar os dados nas tabelas dimensionais e fato. Os arquivos CSV gerados durante o processo de ETL são os seguintes:

**Multas:**
- dim_date_multa.csv: Tabela dimensão que contém informações sobre as datas relacionadas às multas.
- dim_uf.csv: Tabela dimensão que contém informações sobre os estados relacionados às multas.
- dim_escopo_autuacao.csv: Tabela dimensão que contém informações sobre os escopos de autuação das multas.
- fact_quantidade_autos.csv: Tabela fato que contém a quantidade de autos de multas.

**Covid:**
- dim_city.csv: Tabela dimensão que contém informações sobre as cidades relacionadas à Covid-19.
- dim_state.csv: Tabela dimensão que contém informações sobre os estados relacionados à Covid-19.
- dim_date.csv: Tabela dimensão que contém informações sobre as datas relacionadas à Covid-19.
- fact_deaths.csv: Tabela fato que contém a quantidade de mortes por Covid-19.

Esses arquivos CSV serão utilizados como fonte de dados para a criação do dashboard no LookerStudio.

## Visualizações

O dashboard desenvolvido no LookerStudio irá conter as seguintes visualizações:

1. **Visão Acumulada por Período**: Um gráfico de linha que demonstra a evolução acumulada das multas de trânsito e dos casos de Covid-19 ao longo do tempo. Será possível visualizar a tendência de aumento ou diminuição das multas e dos casos de Covid-19.

2. **Visão Comparativa do Período Anterior**: Foi criado um gráfico de linha comparando o período atual com o período anterior, tanto para as multas de trânsito quanto para os casos de Covid-19.

3. **Classificação por Ranking das Multas por Tipo e Estado**: Uma tabela classificando as multas por tipo e estado, ordenadas do maior para o menor. Essa visualização permite identificar quais tipos de multas e estados possuem maior incidência.

4. **Classificação por Ranking das Mortes por Cidade/Estado**: Será apresentada uma tabela classificando as cidades/estados por quantidade de mortes relacionadas à Covid-19, ordenadas do maior para o menor. Essa visualização permitirá identificar quais cidades ou estados estão mais afetados pela Covid-19 em termos de mortalidade.

## Resumo

Neste projeto, foi desenvolvido um dashboard utilizando o LookerStudio como ferramenta de visualização e Python como ferramenta de ETL. Foram gerados 8 arquivos CSV durante o processo de ETL, contendo as tabelas dimensionais e fato relacionadas às multas de trânsito e aos dados de Covid-19. 

O dashboard apresenta visualizações que permitem analisar a evolução das multas e dos casos de Covid-19 ao longo do tempo, comparar períodos, classificar as multas por tipo e estado, e classificar as cidades/estados por quantidade de mortes. 

Essas visualizações são úteis para auxiliar na compreensão dos dados e na tomada de decisões com base nas informações apresentadas.
