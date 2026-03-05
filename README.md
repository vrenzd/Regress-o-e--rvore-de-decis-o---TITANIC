# 🚢 Análise de Regressão e Árvore de Decisão - TITANIC

## 📋 Descrição do Projeto

Este projeto apresenta uma análise completa e detalhada do famoso conjunto de dados do Titanic, utilizando técnicas de **Regressão** e **Árvore de Decisão** para modelagem preditiva. O objetivo é explorar padrões nos dados dos passageiros do Titanic e construir modelos capazes de prever a sobrevivência.

## 🎯 Objetivos

- Realizar análise exploratória dos dados (EDA)
- Pré-processar e preparar dados para modelagem
- Implementar modelos de **Regressão Logística**
- Implementar modelos de **Árvore de Decisão**
- Comparar desempenho dos modelos
- Avaliar importância das features
- Gerar insights sobre fatores que influenciam a sobrevivência

## 📊 Estrutura do Projeto

```
Regress-o-e--rvore-de-decis-o---TITANIC/
├── titanic_analysis.ipynb    # Notebook principal com toda análise
└── README.md                 # Este arquivo
```

## 📁 Conteúdo do Notebook

### 1. **Importação e Carregamento de Dados**
   - Importação de bibliotecas necessárias (pandas, numpy, scikit-learn, matplotlib, seaborn)
   - Carregamento do dataset do Titanic
   - Visualização inicial dos dados

### 2. **Análise Exploratória de Dados (EDA)**
   - Informações gerais sobre o dataset
   - Estatísticas descritivas
   - Análise de valores faltantes
   - Distribuição de variáveis
   - Correlações entre features
   - Visualizações gráficas

### 3. **Pré-processamento de Dados**
   - Tratamento de valores faltantes
   - Codificação de variáveis categóricas
   - Normalização/Padronização de features
   - Divisão entre conjunto de treino e teste

### 4. **Modelagem com Regressão**
   - Implementação de Regressão Logística
   - Treinamento do modelo
   - Avaliação e métricas de desempenho
   - Análise de coeficientes

### 5. **Modelagem com Árvore de Decisão**
   - Implementação de Decision Tree
   - Treinamento do modelo
   - Visualização da árvore
   - Avaliação e métricas de desempenho
   - Análise de importância das features

### 6. **Comparação de Modelos**
   - Métricas comparativas (Acurácia, Precisão, Recall, F1-Score)
   - Matriz de confusão
   - Curvas ROC
   - Recomendações

## 🛠️ Tecnologias Utilizadas

| Biblioteca | Versão | Uso |
|------------|--------|-----|
| **Python** | 3.x | Linguagem principal |
| **Pandas** | - | Manipulação e análise de dados |
| **NumPy** | - | Computações numéricas |
| **Scikit-learn** | - | Machine Learning e modelagem |
| **Matplotlib** | - | Visualização de dados |
| **Seaborn** | - | Visualizações estatísticas avançadas |
| **Jupyter Notebook** | - | Ambiente interativo |

## 📈 Dataset - Titanic

**Fonte:** Kaggle / UCI Machine Learning Repository

**Dimensões:** Centenas de registros com 12+ features

**Variável Alvo:** `Survived` (0 = Não sobreviveu, 1 = Sobreviveu)

**Features principais:**
- `PassengerId`: ID único do passageiro
- `Pclass`: Classe do passageiro (1ª, 2ª, 3ª)
- `Name`: Nome do passageiro
- `Sex`: Sexo (male/female)
- `Age`: Idade em anos
- `SibSp`: Número de irmãos/cônjuges a bordo
- `Parch`: Número de pais/filhos a bordo
- `Ticket`: Número do ticket
- `Fare`: Tarifa paga
- `Cabin`: Número da cabine
- `Embarked`: Porto de embarque

## 📊 Métricas de Avaliação

Os modelos são avaliados usando:

- **Acurácia**: Proporção de predições corretas
- **Precisão**: Proporção de positivos preditos que são realmente positivos
- **Recall (Sensibilidade)**: Proporção de positivos reais que foram identificados
- **F1-Score**: Média harmônica entre precisão e recall
- **Matriz de Confusão**: Visualização de erros
- **Curva ROC / AUC**: Desempenho em diferentes thresholds

## 🚀 Como Usar

### Pré-requisitos
```bash
Python 3.7+
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Executar o Notebook
```bash
jupyter notebook titanic_analysis.ipynb
```

Então execute as células na sequência recomendada para reproduzir toda a análise.

## 📌 Principais Insights

(Estes serão gerados após executar o notebook)

- Fatores determinantes para sobrevivência
- Distribuição demográfica dos sobreviventes
- Performance comparativa dos modelos
- Recomendações de qual modelo usar

## 🔍 Resultados Esperados

O projeto fornece:
- ✅ Modelos treinados e avaliados
- ✅ Comparação entre técnicas de ML
- ✅ Visualizações explicativas
- ✅ Recomendações baseadas em dados
- ✅ Código comentado e documentado

## 💡 Melhorias Futuras

- [ ] Implementar Random Forest e Gradient Boosting
- [ ] Otimizar hiperparâmetros com Grid Search
- [ ] Validação cruzada (K-Fold)
- [ ] Feature engineering avançado
- [ ] Deploy do modelo em API
- [ ] Análise de SHAP values

## 📝 Autor

**Desenvolvido por:** vrenzd

## 📄 Licença

Este projeto é de uso educacional e está disponível para fins de aprendizado.

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Abra uma issue ou faça um pull request.

---

**Última atualização:** 2026-03-05