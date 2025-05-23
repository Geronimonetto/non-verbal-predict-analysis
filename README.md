﻿# 📊 Projeto de Classificação - k-NN vs Random Forest
Este projeto tem como objetivo aplicar e comparar algoritmos de classificação supervisionada (k-NN e Random Forest) para prever categorias de um conjunto de dados, analisando métricas de desempenho e identificando o melhor modelo com base na acurácia e estabilidade.

## 📁 Estrutura do Projeto

├── Projeto_final_Classificação.ipynb  
├── dados/                             
├── README.md                        
## 📌 Objetivos
Explorar e preparar os dados para classificação

Treinar e avaliar modelos de classificação com validação cruzada

Comparar o desempenho entre k-NN e Random Forest

Identificar o modelo mais eficiente com base nas métricas

## ⚙️ Tecnologias Utilizadas
Python 3.11

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

## 📚 Modelos Avaliados
### 🔹 k-Nearest Neighbors (k-NN)
Melhor valor de k: 4

Acurácia de teste: 78,95%

Acurácia média por validação cruzada: 66,67%

F1-score médio ponderado: 0.73

Limitações: baixo desempenho em classes com poucos exemplos

### 🔸 Random Forest
Melhor combinação de parâmetros:

{
  'n_estimators': 200,
  'max_depth': 5
}

- Acurácia de teste: 84,21%

- Acurácia média na validação cruzada: 83,33%

- F1-score ponderado: 0.80

Vantagens: robustez, melhor desempenho geral, boa generalização

## 🔍 Resultados e Conclusão
O modelo Random Forest superou o k-NN em termos de acurácia, estabilidade e desempenho geral. Apesar de ambos os modelos apresentarem dificuldades em prever classes com baixa representatividade, a Random Forest mostrou-se mais eficaz e consistente, sendo o modelo recomendado para esse conjunto de dados.

## 📈 Próximos Passos
Implementar técnicas para lidar com classes desbalanceadas (como SMOTE)

Explorar outros algoritmos (SVM, Gradient Boosting, etc.)

Aplicar normalização de dados para melhorar o desempenho do k-NN

Criar uma interface simples (ex: Streamlit) para visualização dos resultados
