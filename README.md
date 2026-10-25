# hydro-inflow-similarity-page

Páginas estáticas da projeção de ENA por subsistema e dos anos similares ao regime de ENSO (modelo-v1).

- `hydro_inflow_similarity/index.html`: projeção de ENA (modelo-v1 a partir do mês em curso), Sudeste agregado e por bloco,
  anos similares, camada de El Niño forte, modelos-sombra e rodadas.
- `hydro_inflow_similarity/clima.html`: indicadores climáticos (14 índices da NOAA) e a previsão oficial do ENSO do CPC.
- `hydro_inflow_similarity/fundamentos.html`: o que 95 anos de ENA mostram sobre o ENSO e as outras variáveis.
- `hydro_inflow_similarity/metodologia.html`: método, exemplo com números, desempenho fora da amostra e testes.
- `padrao/`: padrão visual Quant Energia (estilos e funções de gráfico).

Os arquivos de dados (`hydro_inflow_similarity/dados*.js`) são gerados pelo repositório `hydro-inflow-similarity-analytics`:

```
uv run python -m hydro_inflow_similarity_analytics.web --site ../hydro-inflow-similarity-page
```

Não editar os arquivos de dados à mão. Para abrir localmente, basta abrir `index.html` no navegador.
