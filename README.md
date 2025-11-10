# HealthCare Data Analysis Project

## 📌 Descrição
Este projeto tem como objetivo analisar dados simulados de saúde para gerar insights que podem melhorar o atendimento ao paciente. O projeto abrange todo o ciclo de Ciência de Dados, desde a **coleta e pré-processamento dos dados**, passando por **análise exploratória**, até **modelagem preditiva** e visualização interativa.

O projeto foi realizado utilizando Python e ferramentas de análise de dados, com um dataset simulado de pacientes, contendo informações como idade, gênero, tipo de atendimento e indicadores de saúde.

---

## 🎯 Objetivos
- Coletar e organizar dados simulados de saúde.
- Limpar e pré-processar os dados, tratando valores ausentes e duplicados.
- Realizar análise exploratória (EDA) com gráficos, histogramas e heatmaps.
- Construir modelo de **Machine Learning supervisionado** para prever indicadores importantes (ex.: risco de readmissão hospitalar).
- Criar dashboards e visualizações interativas para apresentar insights de forma clara e acessível.

---

## 🗂 Estrutura do Projeto
healthcare_project/
│
├── data/
│ └── healthcare_data.csv # Dataset simulado
│
├── notebooks/
│ └── healthcare_analysis.ipynb # Notebook com todo o pipeline
│
├── reports/
│ └── healthcare_report.pdf # Relatório com prints e insights
│
├── README.md
└── requirements.txt # Dependências do projeto


---

## 🛠 Tecnologias Utilizadas
- **Python 3.11**
- Bibliotecas:
  - `pandas`, `numpy` (manipulação de dados)
  - `matplotlib`, `seaborn` (visualização)
  - `scikit-learn` (modelagem preditiva)
- Jupyter Notebook

---

## 📊 Principais Etapas do Projeto

### 1. Coleta de Dados
O dataset utilizado está disponível [neste link CSV](https://github.com/seu-usuario/healthcare_project/blob/main/data/healthcare_data.csv).

### 2. Pré-processamento e Estatísticas Descritivas
- Limpeza de dados, tratamento de valores ausentes e duplicados.
- Transformação de variáveis categóricas e normalização de dados numéricos.
- Estatísticas descritivas gerais (média, mediana, desvio padrão, etc.)

📸 **Print do código e outputs de pré-processamento:**  
![Pré-processamento](reports/print_preprocessamento.png)

### 3. Análise Exploratória (EDA)
- Visualizações: histogramas, gráficos de barras, heatmaps de correlação.
- Identificação de padrões, outliers e tendências nos dados.

📸 **Print dos gráficos de análise exploratória:**  
![EDA](reports/print_eda.png)

### 4. Modelagem Preditiva
- Algoritmo: Regressão Logística / Random Forest (exemplo de previsão de risco de readmissão hospitalar)
- Avaliação do modelo: matriz de confusão, acurácia, precisão, recall e F1-score.

📸 **Print da matriz de confusão e métricas:**  
![Modelo](reports/print_modelo.png)

### 5. Visualização Interativa
- Dashboards criados para apresentar insights e KPIs importantes.
- Facilita a interpretação e tomada de decisões estratégicas.

📸 **Print do dashboard final:**  
![Dashboard](reports/print_dashboard.png)

---

## 📁 Como Executar

1. Clone este repositório:
```bash
git clone [https://github.com/seu-usuario/healthcare_project.git
](https://github.com/hobsonmaciel/healthcare_project)
