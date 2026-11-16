# Titanic: Machine Learning from Disaster

Baseline para a competição do Kaggle que prevê quais passageiros sobreviveram ao naufrágio do Titanic.

## Abordagem
- Features: Pclass, Sex, SibSp, Parch
- Pré-processamento: one-hot encoding (`pd.get_dummies`)
- Modelo: RandomForestClassifier (100 árvores, profundidade máxima 5)

## Resultado
- Score público no Kaggle: 0.77511

## Como reproduzir
1. Baixe os dados em https://www.kaggle.com/competitions/titanic
2. Abra `notebookbd0e38e6db.ipynb` e execute todas as células

## Próximos passos
- Usar Age e Fare e tratar valores ausentes
- Testar outros modelos e validação cruzada
