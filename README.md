# Manipulação de Dados

Repositório de trabalhos desenvolvidos durante os estudos de **Manipulação de Dados**, com aplicações em **R, SQL/SQLite, Python e Polars**.

Os projetos abordam diferentes etapas do processo de análise de dados: **importação, limpeza, transformação, armazenamento, consulta, análise, visualização e processamento eficiente**.

---

## 📌 Competências desenvolvidas

* Manipulação e transformação de dados
* Tratamento de dados faltantes e inconsistências
* Processamento de arquivos em chunks
* Bancos de dados relacionais e SQLite
* Consultas SQL e operações com `JOIN`
* Análise exploratória e visualização de dados
* Manipulação de DataFrames com R e Python
* Processamento de dados com Polars
* Documentação e geração de relatórios com Quarto

---

# 🗂️ Trabalhos e projetos

## ✈️ Desafio 4 — Análise de voos e trajetos de aeronaves

**Tecnologias:** R, tidyverse, readr, geosphere, leaflet, Quarto

Análise de dados de voos com foco no acompanhamento dos trajetos de uma aeronave específica.

O arquivo `flights.csv` é processado em **chunks de 100.000 registros**, permitindo trabalhar com um grande volume de dados sem carregá-lo integralmente na memória.

O trabalho realiza a integração de informações de voos, aeroportos e companhias aéreas, além do cálculo de **distâncias, duração dos voos e velocidade média**. Os resultados são apresentados por meio de uma **tabela interativa e um mapa dos trajetos**.

**Competências:** processamento de dados, integração de bases, análise geográfica e visualização interativa.

---

## 🗄️ Desafios 5–7 — Bancos de dados e SQL

**Tecnologias:** R, DBI, RSQLite, dplyr, dbplyr

Conjunto de trabalhos voltados à utilização de **bancos de dados relacionais a partir do R**.

São exploradas conexões com SQLite, criação e manipulação de tabelas e consultas utilizando **SQL e `dbplyr`**, incluindo filtros, ordenações, agregações e `JOINs`.

Os exercícios utilizam dados relacionados a **músicas, álbuns, clientes e vendas**, permitindo trabalhar com diferentes estruturas relacionais.

**Competências:** SQL, bancos relacionais, SQLite e integração entre R e bancos de dados.

---

## 🛫 Desafio 9 — Processamento de dados de voos com SQLite

**Tecnologias:** R, RSQLite, readr, SQLite

Construção de um banco de dados SQLite a partir de dados de voos.

O trabalho utiliza **processamento em chunks** para filtrar os registros de interesse do `flights.csv` e armazená-los de forma incremental no banco.

São realizadas a criação das tabelas, importação dos dados, filtragem por aeroportos e consultas sobre os dados armazenados.

**Competências:** processamento de grandes arquivos, SQLite, armazenamento incremental e manipulação de dados relacionais.

---

## 🐍 Desafio 10 — Manipulação de dados com Polars

**Tecnologias:** Python, Polars

Aplicação do **Polars** para manipulação e análise de dados de aeroportos e voos.

O trabalho envolve leitura de arquivos, criação e transformação de DataFrames, tratamento de valores ausentes, estatísticas descritivas, filtragem, ordenação, agrupamentos e agregações.

Também são realizadas **junções entre diferentes conjuntos de dados**.

**Competências:** Python, Polars, transformação de dados e análise exploratória.

---

## 🗃️ Desafio 12 — Integração entre Python, Polars e SQLite

**Tecnologias:** Python, Polars, SQLite

Projeto que integra **Python, Polars e SQLite** em uma análise de dados de vendas.

São criadas e consultadas tabelas SQLite, com os resultados sendo posteriormente manipulados em DataFrames Polars.

A análise inclui **agregações de vendas, cálculo de totais e médias, filtros, `INNER JOIN` e criação de métricas derivadas, como lucro**.

**Competências:** Python, SQL, SQLite, Polars e integração entre bancos de dados e DataFrames.

---

## 🎬 Desafio 13 — Análise de dados do IMDb com SQL

**Tecnologias:** R, SQLite, SQL, DBI, RSQLite

Análise de dados do **IMDb** utilizando arquivos `.tsv.gz` e múltiplas tabelas relacionadas.

Os dados são armazenados em SQLite e analisados por meio de consultas SQL envolvendo **`JOINs`, agregações, filtros e ordenações**.

Entre as análises estão o ranking de filmes com maiores avaliações, a frequência de gêneros entre filmes bem avaliados e a participação de atores e atrizes nesses filmes.

**Competências:** SQL, bancos relacionais, análise de dados e manipulação de bases reais.

---

## 💎 Desafio 14 — Análise e visualização de dados

**Tecnologias:** Python, pandas, Plotnine

Análise exploratória do conjunto de dados **Diamonds**, investigando a relação entre características dos diamantes e seus preços.

São analisadas variáveis como **peso (`carat`), preço, qualidade do corte e clareza**.

O trabalho utiliza visualizações, **escalas logarítmicas e regressão linear** para investigar a relação entre peso e preço e comparar esse comportamento entre diferentes categorias de qualidade.

**Competências:** Python, pandas, visualização de dados e análise de relações entre variáveis.

---

# 🛠️ Tecnologias utilizadas

| Tecnologia       | Aplicação                                    |
| ---------------- | -------------------------------------------- |
| **R**            | Manipulação, análise e visualização de dados |
| **SQL / SQLite** | Bancos relacionais e consultas               |
| **Python**       | Manipulação e visualização de dados          |
| **Polars**       | Processamento e transformação de DataFrames  |
| **pandas**       | Manipulação e análise de dados               |
| **Quarto**       | Documentação e geração de relatórios         |
| **Git / GitHub** | Versionamento e organização dos projetos     |

---

# 🎯 Objetivo do repositório

Este repositório reúne trabalhos acadêmicos desenvolvidos para consolidar conhecimentos em **manipulação, armazenamento, consulta, análise e visualização de dados**.

Os projetos exploram diferentes ferramentas e abordagens, desde o tratamento de dados brutos e processamento de grandes arquivos até a utilização de **bancos relacionais, SQL, análise exploratória e visualização de dados**.

---

# 👨‍💻 Autor

**Eduardo Amorim**

Graduando em Estatística pela **Universidade Estadual de Campinas (UNICAMP)**, com interesse em **Ciência de Dados, Machine Learning, análise estatística e programação aplicada a dados**.
