# Implementação do Algoritmo K-means com o Dataset HAR

Este projeto demonstra a implementação do algoritmo K-means para clusterização de dados de atividades humanas. O dataset utilizado é o "Human Activity Recognition Using Smartphones", que contém dados coletados de acelerômetro e giroscópio de smartphones.

**Link para o dataset:** https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

**Bibliotecas utilizadas:**

- Pandas
- Scikit-learn
- Matplotlib

**Etapas do Projeto:**

1. **Carregamento e Preparação dos Dados:**
   - Carga do dataset a partir de arquivos de texto.
   - Limpeza e organização dos dados em DataFrames do Pandas.
   - Separação dos dados em conjuntos de treino e teste.

2. **Análise Exploratória dos Dados:**
   - Visualização da distribuição dos dados.
   - Análise da matriz de correlação entre as variáveis.

3. **Redução de Dimensionalidade com PCA:**
   - Aplicação do PCA para reduzir a dimensionalidade dos dados.
   - Visualização dos dados após a redução.

4. **Determinação do Número Ideal de Clusters (K):**
   - Utilização do método do cotovelo e Silhouette Score para encontrar o valor ideal de K.

5. **Implementação do K-means:**
   - Inicialização do algoritmo com o K-means++.
   - Ajuste do modelo aos dados.
   - Obtenção dos clusters.

6. **Visualização e Avaliação dos Resultados:**
   - Visualização dos clusters em um gráfico de dispersão.
   - Cálculo do Silhouette Score para avaliar a qualidade dos clusters.

**Observações:**

- O código foi implementado em Python.
- O número ideal de clusters foi determinado como 2.
- O Silhouette Score obtido foi 0.70, indicando uma boa qualidade dos clusters.
