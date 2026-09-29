# Titanic - Machine Learning from Disaster

## 📋 Descrição
Projeto de Machine Learning para prever a sobrevivência de passageiros do Titanic.
Desenvolvido como parte dos estudos de Ciência de Dados.

## 🎯 Resultado
- Modelo: Random Forest
- Acurácia local: 81.6%
- Pontuação Kaggle: 0.74401

## 📁 Estrutura do Projeto
titanic/
├── data/
│ ├── raw/ # Dados originais do Kaggle
│ ├── processed/ # Dados após limpeza
│ └── output/ # Submissões geradas
├── notebooks/ # Jupyter notebooks
├── src/ # Código Python reutilizável
├── models/ # Modelos salvos
├── reports/ # Gráficos e relatórios
├── README.md
└── requirements.txt

## 🛠️ Tecnologias
- Python 3.13
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 🚀 Como executar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Abra o notebook: `notebooks/Titanic_DS.ipynb`

## 📊 Principais descobertas
- Mulheres tiveram taxa de sobrevivência de 74%
- Passageiros de 1ª classe sobreviveram 63% das vezes
- O valor da passagem (Fare) foi a feature mais importante