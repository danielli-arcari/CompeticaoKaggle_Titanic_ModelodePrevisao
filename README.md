# Titanic - Modelo de Previsão de Sobrevivência

Projeto de Machine Learning desenvolvido a partir da competição **Titanic - Machine Learning from Disaster**, da plataforma Kaggle.

O objetivo do projeto é construir um modelo capaz de prever quais passageiros sobreviveram ao naufrágio do Titanic a partir de características como sexo, idade, classe do passageiro, tarifa paga e informações familiares.

## Resultado no Kaggle

O modelo foi submetido oficialmente à competição Titanic no Kaggle.

| Métrica | Resultado |
|---|---:|
| Score Kaggle | **0.76555** |
| Melhor score obtido | **0.76555** |
| Versão da submissão | V2 |

Esse resultado corresponde a uma acurácia aproximada de **76,56%** na avaliação realizada pelo Kaggle.

## Competição

**Titanic - Machine Learning from Disaster**

[Kaggle - Titanic](https://www.kaggle.com/competitions/titanic)

A competição propõe um problema clássico de Machine Learning: utilizar os dados conhecidos dos passageiros do Titanic para prever quais deles sobreviveram ao desastre.

## Objetivo

Desenvolver um modelo de **classificação binária** capaz de prever a variável `Survived`.

A variável possui dois possíveis valores:

- `0` - passageiro não sobreviveu
- `1` - passageiro sobreviveu

## Base de dados

As bases utilizadas foram disponibilizadas pelo próprio Kaggle e estão armazenadas na pasta `BaseDadosTitanic`.

### Arquivos

- `train.csv` - conjunto de dados utilizado para análise e treinamento dos modelos
- `test.csv` - conjunto de dados utilizado para gerar as previsões finais
- `gender_submission.csv` - exemplo de submissão disponibilizado pelo Kaggle

### Principais variáveis

| Variável | Descrição |
|---|---|
| `PassengerId` | Identificador do passageiro |
| `Survived` | Indica se o passageiro sobreviveu |
| `Pclass` | Classe da passagem |
| `Name` | Nome do passageiro |
| `Sex` | Sexo |
| `Age` | Idade |
| `SibSp` | Número de irmãos/cônjuges a bordo |
| `Parch` | Número de pais/filhos a bordo |
| `Ticket` | Número do bilhete |
| `Fare` | Tarifa paga |
| `Cabin` | Cabine |
| `Embarked` | Porto de embarque |

## Etapas do projeto

O desenvolvimento do projeto envolveu as seguintes etapas:

1. Importação das bibliotecas
2. Carregamento das bases de dados
3. Exploração inicial dos dados
4. Análise das variáveis
5. Identificação de valores ausentes
6. Tratamento e preparação dos dados
7. Seleção das variáveis utilizadas na modelagem
8. Separação dos dados de treinamento e validação
9. Treinamento dos modelos
10. Avaliação do desempenho
11. Comparação entre os modelos
12. Escolha do modelo final
13. Treinamento utilizando os dados disponíveis
14. Previsão da sobrevivência dos passageiros da base de teste
15. Geração do arquivo de submissão
16. Submissão do resultado ao Kaggle

## Modelos de Machine Learning

Foram utilizados e comparados modelos de classificação para avaliar diferentes abordagens de previsão.

### Regressão Logística

A Regressão Logística foi utilizada como um dos modelos de classificação para estimar a probabilidade de sobrevivência dos passageiros.

É um algoritmo bastante utilizado como modelo de referência em problemas de classificação binária.

### Random Forest

Também foi utilizado o algoritmo **Random Forest**, que combina diversas árvores de decisão para produzir as previsões.

A comparação entre os modelos permitiu avaliar qual abordagem apresentava melhor desempenho antes da geração da submissão final.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Kaggle
- Git
- GitHub

## Estrutura do repositório

```text
CompeticaoKaggle_Titanic_ModelodePrevisao/
│
├── BaseDadosTitanic/
│   ├── train.csv
│   ├── test.csv
│   └── gender_submission.csv
│
├── competicaotitanic.ipynb
│
└── README.md

## Notebook

Todo o processo de análise, preparação dos dados, treinamento dos modelos e geração das previsões está documentado no arquivo:

competicaotitanic.ipynb

## Conhecimentos aplicados

## Durante o desenvolvimento do projeto foram aplicados conceitos de:

Análise Exploratória de Dados
limpeza e tratamento de dados
tratamento de valores ausentes
preparação de variáveis
seleção de atributos
classificação binária
treinamento de modelos de Machine Learning
validação de modelos
comparação de algoritmos
geração de previsões
avaliação de desempenho
criação de arquivos para submissão
utilização da plataforma Kaggle
Resultado final

O projeto resultou na construção de um pipeline completo, desde o carregamento e preparação dos dados até a geração das previsões e submissão do modelo em uma competição real de Machine Learning.

## Score obtido no Kaggle: 0.76555

## Autora

Danielli Arcari

Graduanda em Ciência da Computação com foco em Análise de Dados e Ciência de Dados.

GitHub: danielli-arcari
