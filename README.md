# 🎯 Projeto: Classificação de Clientes para Campanhas de Marketing

Este projeto tem como objetivo identificar, por meio de aprendizado de máquina, **quais clientes têm maior propensão a responder positivamente a uma campanha de marketing**. Utilizamos uma abordagem supervisionada de classificação binária.

---

## 📌 Objetivo

Prever quais clientes devem ser selecionados para campanhas de marketing, com base em variáveis como gastos, idade, filhos, estado civil, entre outras.

---

## 🔍 Etapas do Projeto

1. **Pré-processamento**
   - Análise de correlação e limpeza de variáveis irrelevantes
   - Codificação de variáveis categóricas
   - Padronização com `StandardScaler`

2. **Modelagem**
   - Teste com vários modelos: Logistic Regression, Random Forest, SVM, etc.
   - Escolha dos melhores: `RandomForest` e `LogisticRegression`

3. **Avaliação**
   - Métricas: Accuracy, F1-Score, ROC AUC
   - Matriz de Confusão
   - Curva ROC

4. **Ajuste de Hiperparâmetros**
   - Uso de `GridSearchCV` para otimizar o Random Forest
   - Obteve-se **F1 = 1.00** com parâmetros otimizados

---

## ✅ Resultado Final

O modelo `Random Forest` com hiperparâmetros otimizados apresentou **resultado perfeito (F1 = 1.00)** na base de teste. Além disso, sua capacidade de interpretar a importância das variáveis foi essencial para insights de negócio.

---

## 🔧 Tecnologias Utilizadas

- Python
- Pandas / NumPy
- Scikit-learn
- Google Colab
- Matplotlib / Seaborn

---

## 📁 Arquivos no Repositório

- `Projeto.ipynb`: notebook com todo o pipeline
- `modelo_rf_otimizado.joblib`: modelo treinado
- `graficos/`: gráficos de avaliação e importância
- (opcional) `dados_tratados.csv`: base tratada para reuso

---

## 💡 Possíveis Melhorias

- Deploy com Streamlit para interface interativa
- Uso de técnicas de balanceamento se necessário (SMOTE)
- Testar outros algoritmos como XGBoost
- Validação com dados reais de campanhas futuras

---

## ✍️ Autor

Karina Sampaio  
Profissão Cientista de Dados — M37  
[LinkedIn ou GitHub aqui, opcional]

