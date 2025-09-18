# Titanic Machine Learning Project

Análise de sobrevivência do Titanic usando algoritmos de classificação.

## 🎯 Objetivo
Comparar performance de Regressão Logística vs Random Forest na previsão de sobrevivência do Titanic.

## 📊 Dataset
- **Fonte**: [Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Amostras**: 891 passageiros
- **Features**: 10 variáveis após pré-processamento

## 🛠️ Pré-processamento
- Preenchimento de valores missing (Age, Embarked)
- Remoção de colunas irrelevantes (Cabin, PassengerId, Name, Ticket)
- One-hot encoding (Sex, Embarked, Pclass)

## 🤖 Modelos Implementados
1. **Regressão Logística**
   - Configuração padrão
   - max_iter=1000

2. **Random Forest Classifier**
   - n_estimators=100
   - random_state=42

## 📈 Resultados

### Métricas de Performance
| Modelo | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| Random Forest | 81.6% | 79.0% | 71.0% | 74.8% |
| Regressão Logística | 79.9% | 78.0% | 66.7% | 71.9% |

### 🏆 Modelo Vencedor: Random Forest
Superou em todas as métricas, especialmente em recall (+4.3%), indicando melhor capacidade de identificar sobreviventes.

## 🚀 Como Executar
1. Clone o repositório
2. Abra `titanic_analysis.ipynb` no Google Colab ou Jupyter
3. Execute as células sequencialmente

## 📁 Estrutura do Projeto
