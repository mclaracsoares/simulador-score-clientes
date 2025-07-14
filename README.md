# 🧠 Simulador de Score de Crédito com IA

Este projeto simula a análise de risco de crédito de clientes, utilizando técnicas de Machine Learning para prever o **score de crédito** com base em dados financeiros, comportamentais e históricos.

## 👩‍💻 Autor

Maria Clara C Soares

## 💼 Contexto

Criado com base em um desafio prático da **Hashtag Treinamentos**, este projeto foi adaptado e aprofundado por mim com o objetivo de aplicar conhecimentos em **pré-processamento de dados**, **análise exploratória**, **modelagem preditiva** e **interpretação de modelos de IA**.

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

## 🤖 Tecnologias e Bibliotecas Utilizadas

- Python (Pandas, NumPy)
- Scikit-learn (RandomForest, KNN, train_test_split, LabelEncoder, accuracy_score)
- Jupyter Notebook

## 🏆 Resultados

- O modelo **Random Forest** obteve acurácia de **83%**, superando o modelo KNN.
- A variável mais influente no score foi a **dívida total**, seguida por **juros de empréstimo** e **mix de crédito**.

## 📈 Prints

<img width="1280" height="521" alt="image" src="https://github.com/user-attachments/assets/b565d9bd-668a-478b-8d7c-7f0792f73539" />

<img width="1313" height="548" alt="image" src="https://github.com/user-attachments/assets/444b6f20-9947-4a8e-9483-248311940c9b" />

<img width="1297" height="537" alt="image" src="https://github.com/user-attachments/assets/671bbdf6-c09f-43f8-ba87-28316168e461" />

<img width="1291" height="559" alt="image" src="https://github.com/user-attachments/assets/dcf632e5-1e14-4f79-8e29-5522b90545e0" />

<img width="1286" height="545" alt="image" src="https://github.com/user-attachments/assets/65e8d5a5-2116-4ed9-b640-e50658f9644b" />

## 📌 Observações

- Este projeto foi desenvolvido com base em um exercício guiado da Hashtag Treinamentos, mas com compreensão, adaptação e execução pessoal.
- Não foi utilizada nenhuma base real de clientes; os dados são fictícios e gerados para fins educacionais.


