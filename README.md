# Validação Cruzada em SVM aplicado à Predição de Diabetes  

Este repositório contém a implementação da atividade do **3º UMC Summit de Pesquisa, Inovação e Extensão (2025)**, da Universidade de Mogi das Cruzes.  
O objetivo é analisar o impacto da escolha do método de **validação cruzada** no desempenho de modelos de **Support Vector Machine (SVM)** para predição de diabetes, utilizando o dataset **Pima Indians Diabetes**.  

---

## 📌 Conteúdo  
- Pré-processamento com `StandardScaler` (Pipeline).  
- Ajuste de hiperparâmetros via `GridSearchCV`.  
- Comparação entre **KFold-10** e **RepeatedKFold 5x2**.  
- Avaliação com acurácia média, desvio padrão e matriz de confusão.  

---

## 📊 Resultados  
- **Acurácia final (teste):** 73,5% para ambos os métodos.  
- **KFold-10:** validação média de 78,7% (±3,9%).  
- **RepeatedKFold 5x2:** validação média de 78,4% (±6,0%).  
- **Principais diferenças:**  
  - KFold-10 → maior estabilidade entre os folds.  
  - RepeatedKFold 5x2 → capturou maior variação e reduziu falsos negativos.  

---

## 🛠️ Tecnologias  
- Python 3  
- scikit-learn  
- pandas  
- numpy  
- matplotlib  

---

## 🔑 Palavras-chave  
`SVM` · `Machine Learning` · `Validação Cruzada` · `Diabetes` · `Bioinformática`  

---
