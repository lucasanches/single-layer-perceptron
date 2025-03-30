# 📚 Single Layer Perceptron

Este repositório contém a implementação de um **Perceptron de Camada Única** (Single Layer Perceptron - SLP) para classificação binária, desenvolvido como parte da disciplina de **Redes Neurais Artificiais** do Programa de Pós-Graduação em Ciência da Computação (PPGCC - UNESP).

## 🔬 Sobre o Perceptron

O **Perceptron de Camada Única** é um dos primeiros modelos de redes neurais artificiais e funciona como um classificador linear. Ele ajusta seus pesos utilizando a **Regra de Aprendizado de Hebb**, baseada no erro entre a saída prevista e a real.

A função de ativação usada é a **função degrau bipolar**, que retorna 1 ou -1 dependendo da soma ponderada das entradas.

## 🎯 Objetivo da Atividade

Nesta atividade, o Perceptron foi treinado para classificar amostras em duas categorias distintas, utilizando um conjunto de dados de treinamento e teste carregados disponibilizados. O modelo ajusta os pesos iterativamente até convergir para uma solução capaz de separar as classes.

## 🛠 Tecnologias Utilizadas

- Python 3.12.8
- NumPy 2.2.4
- Matplotlib 3.10.1
- Pandas 2.2.3

## 📷 Visualização dos Dados

O código gera gráficos de dispersão que mostram a distribuição das amostras de cada classe no espaço de características, além da reta de separação (fronteira de decisão) aprendida pelo Perceptron.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
