# Agrupamento de Clientes Usando K-means

Este projeto aplica o algoritmo K-means para agrupar clientes de um e-commerce com base em características como renda anual, índice de gastos e idade. O objetivo é identificar diferentes perfis de consumidores.

## Passos Realizados

1. **Preparação dos Dados:**
   - Remoção da coluna `CustomerID`.
   - Normalização dos dados.

2. **Determinação do Número de Clusters:**
   - Utilização do método do cotovelo para escolher o número ideal de clusters.

3. **Aplicação do Algoritmo K-means:**
   - Agrupamento dos clientes em 5 clusters.

4. **Visualização e Avaliação:**
   - Criação de gráficos para visualizar e interpretar os clusters.
   - Cálculo da pontuação de silhueta para avaliar a qualidade dos clusters.

## Resultados

- **Clusters Identificados:**
  - **Cluster 0:** Alta renda e alto índice de gastos.
  - **Cluster 1:** Renda média e gasto médio.
  - **Cluster 2:** Alta renda e baixo índice de gastos.
  - **Cluster 3:** Renda média e gasto médio.
  - **Cluster 4:** Baixa renda e alto índice de gastos.

- **Pontuação de Silhueta:** 0.39 (indicando uma separação razoável dos clusters).
