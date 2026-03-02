# Pizza Price Prediction

> **Sistema de modelagem preditiva baseado em Regressão Linear para estimativa de valores comerciais de produtos com base em dimensões físicas.**

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
</p>

## 1. Escopo Técnico
Este projeto implementa um modelo de aprendizado de máquina supervisionado para prever o preço de pizzas com base no seu diâmetro. A aplicação utiliza uma abordagem de Regressão Linear Simples para estabelecer a correlação entre a variável independente (diâmetro em cm) e a variável dependente (preço em R$), oferecendo uma interface intuitiva para consultas em tempo real.


## 2. Engenharia de Dados e Modelagem

A arquitetura do sistema foi desenvolvida priorizando a clareza e a reprodutibilidade dos experimentos:

* **Manipulação de Dados**: Utilização da biblioteca **Pandas** para o carregamento e estruturação do dataset (`pizzas.csv`).
* **Algoritmo de ML**: Implementação da classe `LinearRegression` da **Scikit-Learn** para o treinamento do modelo preditivo.
* **Deploy de Interface**: Uso do framework **Streamlit** para transformar o modelo em uma aplicação web funcional, permitindo a entrada de dados via usuário e exibição imediata do resultado processado.

## 3. Estrutura do Projeto

```text
machine-learning-project/
 ├── .venv/            # Ambiente virtual de desenvolvimento
 ├── tests/            # Diretório para testes unitários e de integração
 ├── app.py            # Script principal da aplicação Streamlit e lógica do modelo
 ├── pizzas.csv        # Dataset utilizado para o treinamento do algoritmo
 ├── poetry.lock       # Controle de versões de dependências
 ├── pyproject.toml    # Configuração de pacotes e ambiente Poetry
 └── testes.ipynb      # Notebook para exploração de dados e prototipagem
