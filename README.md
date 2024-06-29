### Credit Analysis 

#### Objetivo:
Neste projeto, estamos construindo um credit scoring para cartão de crédito, em um desenho amostral com 15 safras, e utilizando 12 meses de performance.

#### Análise:
- **Coleta de Dados:** Utilizamos dados históricos de clientes, incluindo informações demográficas, financeiras e comportamentais.
- **Pré-processamento de Dados:** Realizamos tratamento de valores ausentes, remoção de outliers e transformação de variáveis categóricas.
- **Modelagem:** Foram treinados dois modelos principais:
  - Gradient Boosting Classifier (GBC) utilizando PyCaret para otimização de hiperparâmetros.
  - Logistic Regression utilizando Scikit-learn.
- **Avaliação de Modelos:** Avaliamos os modelos utilizando métricas como acurácia, precisão, recall e área sob a curva ROC. Realizamos validação cruzada para garantir a robustez dos resultados.

#### Resultados:
- **Modelo Final Escolhido:** O modelo final escolhido foi o Gradient Boosting Classifier, devido ao seu desempenho superior nas métricas de avaliação.
- **Aplicação Web:** Desenvolvemos uma aplicação web utilizando Streamlit para facilitar a demonstração e uso dos modelos. A aplicação permite carregar arquivos CSV ou FTR.

![Captura de Tela (111)](https://github.com/Bruxteclas/Credit_Scoring/assets/144251717/f5a89a7d-6d16-4985-8b01-5b89078509fd)
