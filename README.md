# Iris Species - Machine Learning
### [Autor: Lucas Barbosa Nascimento](https://github.com/Lucasbnas435)

O modelo de Machine Learning realiza classificação multiclasse (multiclass classification), prevendo se determinada amostra vegetal pertence à espécie _Iris setosa_, _Iris versicolor_ ou _Iris virginica_.

## Dataset
Cada linha desse conjunto de dados representa uma amostra vegetal, contendo medidas da flor colhida e a indicação de sua espécie.

Colunas:

- Id
- SepalLengthCm: Comprimento da sépala em centímetros
- SepalWidthCm: Largura da sépala em centímetros
- PetalLengthCm: Comprimento da pétala em centímetros
- PetalWidthCm: Largura da pétala em centímetros
- Species: Espécie da planta

## Desenvolvimento do Projeto
A aplicação foi desenvolvida em Python 3.10, utilizando [Jupyter Notebooks](https://jupyter.org/) hospedados e executados na plataforma [Google Colaboratory](https://colab.research.google.com/). Ademais, foram utilizadas as bibliotecas [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), [LightGBM](https://lightgbm.readthedocs.io/en/stable/), [Scikit-learn](https://scikit-learn.org/stable/), [XGBoost](https://xgboost.readthedocs.io/en/stable/) e [Joblib](https://joblib.readthedocs.io/en/stable/).

No notebook data-visualization.ipynb, é realizada a visualização dos dados, expondo gráficos e informações que orientam o processo de Análise Exploratória inicial.

O notebook model-training.ipynb apresenta, em seu início, o tratamento dos dados, além da divisão do dataset entre parte de treinamento e parte de testes. Logo depois, é feito o treinamento dos modelos com os algoritmos LightGBM, XGBoost, Decision Tree e K-Nearest Neighbors (kNN). Por fim, tais modelos são exportados, possibilitando seu compartilhamento e uso em outros locais.

## Resultados
Os modelos produzidos com os algoritmos LightGBM, XGBoost e Decision Tree obtiveram acurácia de **100%**. Esse dado, a matriz de confusão e o classification report estão expostos logo abaixo:

![](https://github.com/Lucasbnas435/ML-Iris-Species/blob/master/src/docs/three-models-results.png?raw=true)

Com o algoritmo K-Nearest Neighbors, por sua vez, alcançou-se uma acurácia de **96,66%**. Esse dado, a matriz de confusão e o classification report são exibidos nesta imagem:

![](https://github.com/Lucasbnas435/ML-Iris-Species/blob/master/src/docs/kNN-results.png?raw=true)

## Estrutura de Pastas
```
.
├── README.md
└── src
    ├── dataset
    │   └── Iris.csv
    ├── docs
    │   ├── kNN-results.png
    │   └── three-models-results.png
    ├── models
    │   ├── DecisionTreeModel.joblib
    │   ├── kNNModel.pkl
    │   ├── LightGBMModel.pkl
    │   └── XGBoostModel.json
    └── notebooks
        ├── data-visualization.ipynb
        └── model-training.ipynb
```

## Fonte dos Dados
https://www.kaggle.com/datasets/uciml/iris/data

## Contato
Muito obrigado por acessar esse projeto!

Vamos nos conectar?

- GitHub: https://github.com/Lucasbnas435
- LinkedIn: https://linkedin.com/in/lucasbnas
- E-mail: lucasbnas435@gmail.com