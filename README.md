# Projeto de Análise de Dados do Titanic

Este projeto realiza uma análise exploratória de dados do famoso conjunto de dados do Titanic, disponível no Kaggle, e constrói um modelo de Machine Learning para prever a sobrevivência dos passageiros com base em diversas variáveis.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- **1. Carregamento e Análise Exploratória dos Dados:**
  - Carregamento dos dados e verificação inicial.
  - Análise estatística descritiva.
  - Visualizações para entender a distribuição das variáveis e a relação com a variável alvo (sobrevivência).

- **2. Pré-processamento de Dados:**
  - Tratamento de valores nulos.
  - Engenharia de features para melhorar o desempenho do modelo.
  - Transformação de variáveis categóricas em variáveis dummy.

- **3. Construção do Modelo de Machine Learning:**
  - Divisão dos dados em conjuntos de treino e teste.
  - Escalonamento das variáveis numéricas.
  - Treinamento de um modelo de Regressão Logística para prever a sobrevivência.

- **4. Avaliação do Modelo:**
  - Avaliação da acurácia do modelo treinado.
  - Análise da matriz de confusão para verificar falsos positivos e falsos negativos.
  - Relatório de classificação para métricas detalhadas de precisão, recall e F1-score.

- **5. Visualizações Adicionais:**
  - Visualizações complementares, como a matriz de correlação e gráficos exploratórios.

## Como Usar o Projeto

### Pré-requisitos

- Python 3.x instalado.
- Pacotes necessários podem ser instalados via `pip install -r requirements.txt`.

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Instale os Requisitos:

    ```bash
    pip install -r requirements.txt

### Execute o Notebook

1. Inicie o Jupyter
    ```bash
      jupyter notebook

## Resultados
O modelo treinado alcançou uma acurácia de aproximadamente 80% na previsão da sobrevivência dos passageiros do Titanic.

