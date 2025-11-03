## Modelo de regressão de preços de residência com Python. 

## Descrição do Projeto

Este projeto de Ciência de Dados tem como objetivo principal desenvolver um modelo de **Regressão Linear** em Python para realizar a previsão de preços de apartamentos e residências. O foco está em aplicar técnicas de **Análise Exploratória de Dados (EDA)**, tratamento de dados e modelagem para fornecer uma estimativa precisa no mercado imobiliário.

O pipeline de análise foi projetado para demonstrar proficiência na manipulação, limpeza e preparação de dados para fins preditivos.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Análise Numérica:** NumPy
* **Visualização de Dados:** Matplotlib e Seaborn
* **Modelagem Estatística/ML:** Scikit-learn (para Regressão Linear)
* **Ambiente:** Jupyter Notebook / Google Colab

## 🛠️ Funcionalidades e Metodologia

O projeto segue as principais etapas de um fluxo de trabalho de Machine Learning:

1.  **Análise Exploratória de Dados (EDA):**
    * Identificação e análise de correlações entre as variáveis (`Preço`, `Área`, `Quartos`, etc.).
    * Visualizações para identificar *outliers* e distribuições dos dados.
2.  **Pré-processamento e Tratamento de Dados:**
    * Tratamento de valores ausentes (se houver).
    * Utilização da transformação logarítmica (como visto no notebook) para normalizar a variável alvo (`Preço`), essencial para a Regressão Linear.
3.  **Modelagem Preditiva:**
    * Separação dos dados em conjuntos de Treino e Teste.
    * Implementação do algoritmo de **Regressão Linear**.
    * Avaliação de desempenho usando métricas como $R^2$ e Erro Quadrático Médio (MSE).
4.  **Inferência:**
    * Demonstração da aplicação do modelo treinado para prever o preço final de um imóvel a partir de um novo *input* de dados.

## 📈 Resultado (Exemplo de Previsão)

O modelo final é capaz de prever o preço de um imóvel com base em suas características. O notebook demonstra a aplicação prática, fornecendo o preço sugerido (em $), validando a capacidade preditiva do algoritmo.

## Como Executar o Projeto

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/roboberto1403/](https://github.com/roboberto1403/)[NOME_DO_REPO].git
    ```
2.  **Abra o Notebook:**
    * Abra o arquivo `regressao_precos.ipynb` no seu ambiente preferido (Jupyter, VS Code ou Google Colab).
3.  **Execute as Células:**
    * Siga a execução sequencial das células para carregar os dados, realizar a análise, treinar o modelo e visualizar o resultado final da predição.
