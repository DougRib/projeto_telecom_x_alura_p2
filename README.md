
# 📊 Projeto Telecom X - Parte 2: Predição de Evasão de Clientes (Churn)

Este projeto tem como objetivo prever a evasão (churn) de clientes de uma operadora de telecom com base em variáveis relevantes do comportamento e perfil dos usuários. Através da análise exploratória, preparação dos dados e aplicação de modelos de machine learning, buscamos gerar insights estratégicos e modelos preditivos eficazes para apoiar ações de retenção.

---

## 🎯 Objetivo da Análise

O foco principal da análise é **identificar os fatores que mais influenciam a evasão de clientes** e utilizar **modelos de machine learning** para prever a probabilidade de cancelamento dos serviços. A proposta é transformar dados históricos em **ações estratégicas** para reduzir o churn e aumentar a fidelização dos clientes.

---

## ⚙️ Preparação dos Dados
🔢 Classificação das Variáveis:
  * Categóricas: gender, contract, payment_method, internet_service, etc.

  * Numéricas: tenure, monthly_charges, total_charges, etc.

🧼 Etapas de Pré-processamento:
  * Tratamento de valores ausentes e dados inconsistentes.

  * Aplicação de One-Hot Encoding para variáveis categóricas.

  * Normalização de variáveis numéricas para algoritmos sensíveis à escala (KNN, SVM).

  * Separação dos dados em conjuntos de treino (70%) e teste (30%) com train_test_split.

---

## 📊 Gráficos e Insights da EDA
  * Durante a análise exploratória (EDA), observamos:

  * Clientes com contratos mensais evadem mais do que os com contratos anuais.

  * Baixo tempo de permanência (tenure) está altamente associado à evasão.

  * Faturas mensais elevadas combinadas com curto tempo de contrato indicam alto risco.

  * Clientes que não utilizam serviços extras (backup, suporte técnico) tendem a evadir.

  * Visualizações como gráficos de barras, matriz de correlação e histogramas foram usadas para evidenciar essas relações.
---

## 🤖 Modelagem e Avaliação
### Modelos Treinados:
  * Regressão Logística

  * Random Forest

  * K-Nearest Neighbors (KNN)
---

## 📈 Métricas Utilizadas:
  * Acurácia

  * Precisão

  * Recall

  * F1-Score

  * Matriz de Confusão
--- 
## 📌 Conclusões Estratégicas
  * Com base nos resultados, recomendamos:

  * Campanhas de retenção nos primeiros meses de contrato.

  * Incentivos para migração para planos anuais.

  * Inclusão de serviços gratuitos como suporte técnico inicial.

  * Melhoria na experiência de pagamento, com alternativas mais confiáveis.

  * Utilização contínua do modelo preditivo para detecção de risco em tempo real.

---

## 📚 Bibliotecas Utilizadas
  * pandas e numpy: manipulação e análise de dados

  * matplotlib e seaborn: visualização

  * scikit-learn: machine learning e métricas
---

## ▶️ Como Executar o Projeto
### ✅ Instale as bibliotecas necessárias:

### 🚀 Execute o notebook no Google Colab ou localmente:
  * Faça o upload dos arquivos da pasta data/.

  * Rode o notebook telecom_churn_modeling.ipynb passo a passo.

  * Os gráficos e modelos serão salvos automaticamente nas respectivas pastas.
---
