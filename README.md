# Predição de Nota do IMDB

Este projeto implementa um modelo de regressão para prever notas do IMDB baseado em dados de filmes, incluindo features numéricas, categóricas e texto (sinopse). O modelo principal é um Random Forest, com suporte para pré-processamento de texto (TF-IDF) e OneHotEncoding de categorias, mas Huber Regressor, Gradient Boosting, XGBoost e CatBoost foram usados para teste.

---

## Pré-requisitos
- Python 3.13.5
- Ambiente virtual recomendado (venv ou conda)

## Instalação
1. Clonar o repositório ou baixar os arquivos do projeto.  

2. Instalar as dependências (disponíveis em requisitos.txt)

## Execução

1. Abra o Jupyter notebook ou Jupyter Lab
2. Abra o arquivo `imdb_explore.ipynb` e execute as células em ordem.
    - Dentro do notebook é possível executar e visualizar:
        - Carregametno e limpeza dos dados;
        - Análise exploratória dos daods;
        - Construção e testes de diferentes modelos de regresssão;
        - Decisão pelo modelo Random Forest para predição de notas do IMDB;
        - Salvamento do modelo em `modelos/rf_pipeline.pkl`;
        - Predição da nota do filme 'The Shawshank Redemption' baseado nos dados recebidos.