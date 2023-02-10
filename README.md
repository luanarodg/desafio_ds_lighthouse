# [LIGHTHOUSE INDICIUM] Desafio Data Science

> Projeto feito para o desafio do Programa Lighthouse da Indicium em data science.


## Sumário

- [Desafio](#desafio)
- [Preparação do Ambiente](#preparação-do-ambiente)
- [Documentos](#documentos)
- [Conclusão](#conclusão)



## Desafio

O objetivo desse desafio é identificar quais máquinas apresentam tendência de falha através de um programa de predição com base nos dados já existentes extraídos dos sensores durante o processo de manufatura.

## Preparação do ambiente

Este projeto foi feito usando alguns pacotes, para rodá-lo, é necessário instalar os requerimentos:

Para instalar, siga estas etapas:
```
pip install -r requirements.txt
```


## Documentos

Para esse programa foram fornecidos dois arquivos:

`desafio_manutencao_preditiva_treino` dataset composto por 6667 linhas, 9 colunas de informação (features) e a variável a ser prevista (“failure_type”).

`desafio_manutencao_preditiva_teste` dataset com 3333 linhas e 8 colunas e não possui a coluna “failure_type”, esta será a variável prevista no modelo.


Com isso, foram gerados outros arquivos como resultado dos modelos feitos com os dados:

`requirements.txt` arquivo onde contem as bibliotecas utilizadas no projeto

`decision_tree.ipynb` notebook contendo modelo de Decision Tree (análise exploratória, modelagem e predição)

`logistic_regression.ipynb` notebook contendo modelo de Logistic Regression (análise exploratória, modelagem e predição)

`random_forest.ipynb` notebook contendo modelo de Random Forest (análise exploratória, modelagem e predição)

`predicted.csv` arquivo contendo a predição final com o resultado de previsão e com apenas duas colunas (rowNumber, predictedValues)

`README.md` presente arquivo contendo as informações do projeto





## Conclusão
Mais resultados e informações de como foi os passos estão dentro dos arquivos, onde está mais detalhado o que foi feito em cada modelo.
