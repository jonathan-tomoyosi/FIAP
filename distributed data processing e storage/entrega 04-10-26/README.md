# Entrega 04/10/2026 — Análise de jogos internacionais de futebol com Spark

Análise do arquivo `results_11ABDR.csv` (resultados de jogos internacionais masculinos de futebol, Kaggle) com Apache Spark, respondendo 10 perguntas. Sem uso de pandas.

## Arquivos

- [`Trabalho_11ABDR.ipynb`](Trabalho_11ABDR.ipynb) — notebook com o código (PySpark + Spark SQL) e as respostas.
- `db/results_11ABDR.csv` — dataset.
- `docker-compose.yml` — ambiente Spark + Jupyter.

## Como executar

```bash
docker compose up -d
```

Abra http://localhost:8888, entre em `work/` e execute `Trabalho_11ABDR.ipynb`.
