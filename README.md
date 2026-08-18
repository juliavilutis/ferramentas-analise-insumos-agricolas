# Ferramentas de Análise de Dados de Insumos Agrícolas

Conjunto de ferramentas em Python para consolidação, extração e análise de registros operacionais de aplicação de insumos agrícolas no setor sucroenergético.

## Módulos
- **extracao_ajuste_doses.ipynb** — extração automatizada de doses de defensivos a partir de campos de texto semiestruturados (regex), com normalização de nomenclatura de produtos
- **calculo_consumo_produto.ipynb** — cálculo de consumo de produto por registro operacional a partir de produção e dose, com validação de consistência
- **regressao_operacional.ipynb** — modelagem estatística (regressão linear e Random Forest) de indicadores operacionais agrícolas

## Stack
`Python` · `pandas` · `scikit-learn` · `regex` · Google Colab

*Ferramentas desenvolvidas em contexto profissional no setor sucroenergético. Nenhum dado operacional é distribuído neste repositório — os notebooks contêm apenas código.*
