# penguin-classification
# Classificação de Espécies de Pinguins

## 🔹 Descrição do Projeto
Este projeto tem como objetivo **prever a espécie de um pinguim** (*Adelie*, *Chinstrap* ou *Gentoo*) a partir de suas características físicas, como comprimento e profundidade do bico, comprimento da nadadeira, peso, sexo e ano da observação.  

O projeto envolve as etapas de **Exploração de Dados (EDA)**, **pré-processamento**, e **treinamento de modelos de classificação**.

---

## 🔹 Dataset
O dataset utilizado é o **Penguin Species Dataset** do Kaggle:

- Link do dataset: [Kaggle Penguins](https://www.kaggle.com/datasets/mubeenshehzadi/penguin-species-dataset)
- Colunas:
  - `Species`: Espécie do pinguim (Alvo)
  - `Bill length`: Comprimento do bico (mm)
  - `Bill depth`: Profundidade do bico (mm)
  - `Flipper length`: Comprimento da nadadeira (mm)
  - `Body mass`: Peso do pinguim (g)
  - `Sex`: Sexo do pinguim (Male/Female)
  - `Year`: Ano da observação

---

## 🔹 Etapas do Projeto

### 1️⃣ Exploração de Dados (EDA)
- Verificação de valores ausentes e duplicados
- Estatísticas descritivas das variáveis
- Visualizações:
  - Distribuição das espécies
  - Boxplots e scatterplots das variáveis
- Observações:  
  - Aqui você pode colocar prints dos gráficos mais interessantes.
  - Exemplo: diferenças claras de tamanho de bico e nadadeira entre espécies.

### 2️⃣ Pré-processamento
- Remoção de colunas desnecessárias (ex: `Unnamed: 0`)
- Tratamento de valores nulos (numéricos com média, categóricos com moda ou "Unknown")
- Conversão de variáveis categóricas em numéricas (`Sex` e `Species`)

### 3️⃣ Treinamento de Modelos
- Modelos testados:
  - **Logistic Regression**
  - **Decision Tree**
- Divisão treino/teste: 70/30, estratificada por espécie

### 4️⃣ Avaliação dos Modelos
- Métricas usadas:
  - **Acurácia**
  - **Matriz de Confusão**
  - **Precision, Recall e F1-Score**
- Observações:  
  - Qual modelo teve melhor desempenho?  
  - Houve confusão entre espécies semelhantes?

---

## 🔹 Conclusões
- Insights importantes descobertos na análise e nos modelos
- Variáveis mais relevantes para distinguir as espécies
- Possíveis melhorias futuras, como testar outros modelos ou fazer feature engineering

---

## 🔹 Como Rodar o Projeto
1. Clone o repositório:
```bash
git clone <seu-repo-url>
