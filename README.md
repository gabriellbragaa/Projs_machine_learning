# Nome do Projeto: Previsão de Evasão e Sucesso Acadêmico de Estudantes

## Descrição do Projeto

Este projeto tem como objetivo desenvolver e comparar modelos de machine learning para prever o resultado acadêmico de estudantes (Evasão, Matrícula, Formatura) utilizando o dataset "Predict Students Dropout and Academic Success" do repositório UCI Machine Learning. Foram explorados e avaliados três algoritmos de classificação: K-Nearest Neighbors (KNN), Regressão Logística e Random Forest, com foco na otimização de hiperparâmetros e análise comparativa de desempenho.

## Base de Dados

O dataset utilizado neste projeto é o **Predict Students Dropout and Academic Success**, disponível no repositório UCI Machine Learning. Ele contém diversas características sobre estudantes e a variável alvo que indica o resultado acadêmico final do estudante.

## Estrutura do Projeto

- `nome_do_seu_notebook.ipynb`: O notebook principal contendo todo o código para importação de dados, análise exploratória, pré-processamento, modelagem, avaliação e análise comparativa.

## Tecnologias e Bibliotecas Utilizadas

- Python
- Google Colab (ambiente de desenvolvimento)
- pandas (manipulação e análise de dados)
- numpy (operações numéricas)
- scikit-learn (modelagem e pré-processamento)
- matplotlib (visualização de dados)
- seaborn (visualização de dados estatísticos)
- ucimlrepo (importação do dataset UCI)

## Como Executar o Projeto

1.  Clone este repositório para sua máquina local ou abra-o diretamente no Google Colab.
2.  Abra o arquivo `nome_do_seu_notebook.ipynb` no Google Colab.
3.  Execute as células do notebook sequencialmente. Certifique-se de ter as bibliotecas necessárias instaladas (elas estão no notebook, mas caso rode localmente, use `pip install -r requirements.txt` se criar um arquivo de requisitos).

## Etapas do Projeto

O notebook está estruturado nas seguintes etapas:

1.  **Importação dos Dados:** Carregamento do dataset.
2.  **Análise dos Dados:** Verificação da estrutura, valores ausentes, tipos de dados e distribuição da variável alvo.
3.  **Pré-processamento:** Codificação de variáveis categóricas (One-Hot Encoding), escalonamento de variáveis numéricas (StandardScaler) e divisão em conjuntos de treino e teste.
4.  **Predições:** Treinamento e avaliação dos modelos KNN, Regressão Logística e Random Forest, incluindo otimização de hiperparâmetros com `GridSearchCV` e validação cruzada.
5.  **Análise Comparativa:** Comparação do desempenho dos modelos baseada em métricas como Accuracy, Precision, Recall e F1-Score, além da análise do impacto do escalonamento.

## Resultados e Análise

A seção de Análise Comparativa no notebook apresenta os resultados detalhados de cada modelo, incluindo tabelas e gráficos para visualizar o desempenho. A análise também discute o impacto do escalonamento nos diferentes algoritmos.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias e novas funcionalidades.


