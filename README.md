# IMDB Rating Prediction

Este projeto implementa um modelo de regressão para prever notas do IMDB baseado em dados de filmes, incluindo features numéricas, categóricas e texto (sinopse). O modelo principal é um Random Forest, com suporte para pré-processamento de texto (TF-IDF) e OneHotEncoding de categorias, mas Huber Regressor, Gradient Boosting, XGBoost e CatBoost foram usados para teste

---

## Pré-requisitos
- Python 3.13.5
- Ambiente virtual recomendado (venv ou conda)

1. Clonar o repositório:  
```bash
git clone <URL_DO_REPO>
cd imdb-rating-prediction