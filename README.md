# Projeto 4 — Ridge Regression e Regularização

Regularização L2 (Ridge) com varredura do parâmetro C (0.1, 0.01, 0.001) e validação cruzada de 10 folds. Melhor configuração: C=0.001, AUC médio ~0.733–0.739.

**Livro:** *Projetos de Ciência de Dados com Python* — Stephen Klosterman (Novatec Editora, 2020)

## Conteúdo

- `projeto.ipynb` — notebook completo, já executado (com todas as saídas e gráficos)
- `Data/` — datasets usados (UCI Credit Card: 5.333 registros, 23 variáveis)

## Como executar

```bash
pip install pandas scikit-learn numpy matplotlib seaborn xlrd
jupyter notebook projeto.ipynb
```

Para as visualizações de árvores (Projeto 5), instale o binário Graphviz (`dot`).
