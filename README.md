# Machine-Learning-Aplicado_II_UEA-2025

# 🤖 Atividade Prática — Machine Learning com Naive Bayes

## 🏫 Projeto Educacional
Este repositório faz parte das atividades práticas do módulo **Machine Learning Aplicado** do curso técnico de Informática.  
O objetivo é **introduzir conceitos de Aprendizado de Máquina (IA)** usando **classificadores Naive Bayes** e conjuntos de dados reais.

---

## 📚 Objetivos de Aprendizagem

1. Compreender o que é **Aprendizado de Máquina (Machine Learning)**.
2. Aprender a usar **classificadores probabilísticos** (Naive Bayes).
3. Aplicar esses modelos a **dados reais de texto**.
4. Avaliar o desempenho do modelo usando **métricas e validação cruzada**.
5. Entender como **diferentes tipos de dados (contagem, binário, TF-IDF)** influenciam o resultado.

---

## 🧠 Conceitos Principais

| Conceito | Explicação |
|-----------|-------------|
| **Naive Bayes** | Modelo baseado no Teorema de Bayes, usado para classificação de dados. |
| **MultinomialNB** | Versão do Naive Bayes que trabalha com **contagem de palavras**. |
| **BernoulliNB** | Versão para **atributos binários** (presença/ausência de palavras). |
| **TF-IDF** | Técnica que avalia a importância de uma palavra no texto (peso por frequência). |
| **Validação Cruzada (CV)** | Divide os dados em partes para testar o modelo várias vezes e medir a média de acertos. |

---

## 🧩 Estrutura do Repositório

📦 Atividade-ML-NaiveBayes
┣ 📜 README.md
┣ 📘 AtividadePaticaMLParte01.ipynb → Introdução e Teorema de Bayes
┣ 📘 AtividadePaticaMLParte02.ipynb → Classificação com MultinomialNB (20 Newsgroups)
┣ 📘 AtividadePaticaMLParte03_BernoulliNB_20Newsgroups.ipynb → Codificação Binária e BernoulliNB
┗ 📁 /datasets → (opcional) conjuntos de dados locais


---

## ⚙️ Requisitos

Antes de começar, instale as bibliotecas necessárias.  
Abra um terminal ou notebook e execute:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn


No Google Colab, basta rodar esta célula:

!pip install seaborn scikit-learn
