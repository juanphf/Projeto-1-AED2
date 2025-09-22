# Análise de Rede de Colaboração de Atores (IMDb Top 1000)

**Alunos:** Juan Pablo e Lucas Gabriel  
**Disciplina:** Algoritmos e Estrutura de Dados II

## 1. Descrição do Projeto

Este projeto realiza uma análise de redes de colaboração entre atores da indústria cinematográfica. Utilizando um dataset com os 1000 filmes e shows de TV mais bem avaliados da plataforma IMDb, o objetivo foi transformar esses dados em um grafo não-direcionado e ponderado para identificar os atores mais influentes, as parcerias mais fortes e a estrutura geral da rede.

## 2. Dataset

A base de dados utilizada foi o **"IMDB Movies Dataset"**, disponível publicamente na plataforma Kaggle.

- **Fonte:** [IMDB Dataset of top 1000 movies and tv shows](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)
- **Conteúdo:** O dataset inclui informações como título do filme, diretor, os quatro atores principais (Star 1-4), gênero, ano de lançamento, nota IMDb, bilheteria, entre outros.

## 3. Ferramentas Utilizadas

- **Linguagem:** Python 3
- **Bibliotecas Principais:**
  - **Pandas:** Para manipulação e limpeza dos dados.
  - **NetworkX:** Para a criação, manipulação e análise do grafo.
  - **Matplotlib & Seaborn:** Para a visualização de dados e da rede.
  - **itertools & collections:** Para otimizações no processamento dos dados.
- **Ambiente:** Google Colab / Jupyter Notebook

## 4. Como Executar

1.  Clone este repositório ou baixe os arquivos.
2.  Abra o arquivo `.ipynb` no Google Colab ou em um ambiente Jupyter local.
3.  Certifique-se de que o arquivo `imdb_top_1000.csv` esteja no mesmo diretório ou acessível pelo notebook.
4.  Execute as células do notebook em ordem.

## 5. Resultados da Análise

A análise do grafo permitiu identificar:
- Os **atores com maior grau de centralidade**, ou seja, aqueles que colaboraram com o maior número de outros atores.
- As **parcerias mais fortes**, identificadas pelas arestas com maior peso (maior número de filmes em comum).
- A **estrutura visual da rede**, destacando um componente gigante principal e componentes menores isolados.
