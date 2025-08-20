# Data-Science-Project

Descrição

Este projeto tem como objetivo explorar, limpar e transformar um dataset de habitação da Califórnia, preparando os dados para análises mais profundas e futuros modelos de Machine Learning.
A base contém informações sobre características demográficas, número de quartos, renda mediana e valores de casas em diferentes regiões.

🔧 Tecnologias Utilizadas:

  .Python 3.x

  .Pandas

  .Matplotlib

  .Seaborn

## 📑 Etapas Realizadas

### 1. Carregamento e Exploração Inicial
- Visualização de amostras do dataset  
- Estatísticas descritivas e verificação de valores nulos  

### 2. Limpeza dos Dados
- Tratamento de valores ausentes (`total_bedrooms`)  
- Conversão de tipos (ex.: `median_income`)  
- Padronização de colunas e categorias  
- Remoção de duplicatas  

### 3. Análise Exploratória
- Histogramas e distribuições  
- Boxplots para detecção de outliers  
- Gráficos de dispersão para relações entre variáveis  
  (ex.: renda mediana vs. valor da casa)  


### 4. Feature Engineering
Criação de novas variáveis:


-people_per_household
-rooms_per_person
-rooms_per_household
-bedroom_ratio
-is_coastal
-income_level (faixas de renda categorizadas)

### 5. Codificação de Variáveis Categóricas


-Aplicação de One-Hot Encoding em ocean_proximity e income_level

📈 Resultados e Insights

-Relação positiva entre renda mediana e valor das casas.

-Identificação de outliers em variáveis como total_rooms e population.

-Novos atributos criados tornaram os dados mais interpretáveis e prontos para modelagem preditiva.

🚀 Próximos Passos

-Aplicar algoritmos de regressão para prever median_house_value.

-Testar modelos supervisionados (ex.: Regressão Linear, Árvore de Decisão, Random Forest).

-Avaliar métricas de desempenho (RMSE, R²).
