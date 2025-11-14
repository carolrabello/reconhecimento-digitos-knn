## ✍️ Projeto: Classificação de Dígitos Manuscritos com Machine Learning

## 📌 Visão Geral

Este é um projeto prático que demonstra os fundamentos de **Machine Learning (Aprendizado de Máquina)** aplicados à **Classificação de Imagens**. O trabalho envolve o desenvolvimento de um modelo capaz de **reconhecer e classificar automaticamente dígitos manuscritos (0 a 9)**.

## 🛠️ Ferramentas e Bibliotecas

* **Linguagem:** Python
* **Modelagem (ML):** Scikit-learn
* **Manipulação de Dados:** NumPy e Pandas
* **Visualização:** Matplotlib e Seaborn
* **Ambiente:** Google Colab

## 🧠 Metodologia e Modelagem

* **Dataset:** Foi utilizado o dataset `load_digits`, um conjunto de dados padrão do Scikit-learn contendo 1.797 imagens de dígitos (8x8 pixels).

<img width="410" height="442" alt="Sem título" src="https://github.com/user-attachments/assets/f05e335b-008e-4da7-a22e-841debd2fb5a" />

* **Pré-processamento:**
    * As imagens foram convertidas (achatadas) para vetores de *features*
    * Aplicação do **StandardScaler** para padronizar os dados
    * O dataset foi dividido em conjuntos de **Treino (80%)** e **Teste (20%)**
* **Algoritmo:** Utilizou-se o classificador **K-Nearest Neighbors (KNN)** com $k=3$ para o treinamento do modelo
* **Avaliação:** O modelo foi avaliado no conjunto de Teste para determinar sua precisão e robustez

## ✅ Resultados Chave

O modelo treinado obteve um desempenho robusto na tarefa de classificação:

* **Acurácia (Accuracy) Final:** O modelo alcançou cerca de **98%** de acerto na previsão dos dígitos.
* **Matriz de Confusão:** A matriz abaixo ilustra o desempenho detalhado por classe. É possível observar um alto índice de acertos ao longo da diagonal principal.

<img width="640" height="547" alt="Sem título" src="https://github.com/user-attachments/assets/75a692a1-5f63-4b84-a239-bbad17287a9d" />

---
## 💡 Aprendizados

O projeto proporcionou experiência prática no **ciclo completo de Machine Learning**: da preparação e pré-processamento dos dados à modelagem, treinamento e avaliação de desempenho de um modelo real.
