# 🧠 Simulador de Score de Crédito com IA

Este projeto simula a análise de risco de crédito de clientes, utilizando técnicas de Machine Learning para prever o **score de crédito** com base em dados financeiros, comportamentais e históricos.

---

## 👩‍💻 Autor

Maria Clara C Soares

---

## 💼 Contexto

Criado com base em um desafio prático da **Hashtag Treinamentos**, este projeto foi adaptado e aprofundado por mim com o objetivo de aplicar conhecimentos em **pré-processamento de dados**, **análise exploratória**, **modelagem preditiva** e **interpretação de modelos de IA**.

---

## 📊 Etapas do Projeto

1. **Importação e visualização da base de dados**
2. **Identificação e correção de inconsistências**
3. **Transformação de variáveis categóricas em numéricas**
4. **Divisão entre base de treino e teste**
5. **Criação e treinamento de dois modelos de IA:**
   - Random Forest Classifier
   - K-Nearest Neighbors (KNN)
6. **Avaliação de desempenho dos modelos**
7. **Predição do score para novos clientes**
8. **Interpretação das variáveis mais relevantes**

---

## 📁 Dados

- **Base de Treino:** `clientes.csv` (100.000 registros)
- **Base de Novos Clientes:** `novos_clientes.csv`

Cada linha representa um cliente e seu histórico mensal com atributos como:
- Idade
- Profissão
- Salário Anual
- N° de Cartões e Empréstimos
- Atrasos
- Comportamento de pagamento
- Score de crédito (rótulo a ser previsto)

---

## 🤖 Tecnologias e Bibliotecas Utilizadas

- Python (Pandas, NumPy)
- Scikit-learn (RandomForest, KNN, train_test_split, LabelEncoder, accuracy_score)
- Jupyter Notebook

---

## 🏆 Resultados

- O modelo **Random Forest** obteve acurácia de **83%**, superando o modelo KNN.
- A variável mais influente no score foi a **dívida total**, seguida por **juros de empréstimo** e **mix de crédito**.

---

## 📈 Prints (ou Gráficos)


---

## 📌 Observações

- Este projeto foi desenvolvido com base em um exercício guiado da Hashtag Treinamentos, mas com compreensão, adaptação e execução pessoal.
- Não foi utilizada nenhuma base real de clientes; os dados são fictícios e gerados para fins educacionais.


