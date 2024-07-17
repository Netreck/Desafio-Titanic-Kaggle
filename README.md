# Projeto de Análise de Dados - Titanic

Este é o meu primeiro projeto de análise de dados, onde explorei o famoso conjunto de dados do Titanic disponível no Kaggle. O objetivo foi construir um modelo de predição de sobrevivência dos passageiros do Titanic usando técnicas básicas de aprendizado de máquina.
## Motivação

Como iniciante na área de dados, este projeto foi uma oportunidade de aplicar o conhecimento adquirido até o momento e aprender na prática. Apesar de ser um modelo inicial, planejo revisá-lo futuramente utilizando novas tecnicas aprendidas para otimizar o modelo e assim verificar minha evolução na área.

## Etapas do Projeto

1. **Obtenção dos Dados**: Utilizei um dataset disponível no Kaggle contendo informações sobre os passageiros do Titanic.
   
2. **Limpeza e Pré-processamento dos Dados**:
   - Removi dados e substitui dados nulos de acordo com a necessidade e excluí tabelas faltantes para garantir a integridade dos dados.
   - Transformei variáveis categóricas em variáveis numéricas usando a técnica `get_dummies`.
   - Normalizei os dados para garantir que todas as variáveis contribuíssem igualmente no modelo de predição, especialmente para o uso do modelo KNN que tem base a distância Euclidiana.

3. **Modelagem e Predição**:
   - Utilizei o algoritmo KNN (K-Nearest Neighbors) como modelo de predição de sobrevivência dos passageiros.
   - A normalização dos dados foi crucial devido à sensibilidade do KNN à escala das variáveis.



