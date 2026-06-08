# 🏋️ GymPredict - Previsão de Cancelamento de Alunos

## 📌 Sobre o Projeto

O GymPredict é um projeto de Ciência de Dados desenvolvido para prever o cancelamento de alunos de academias (Churn Prediction).

O objetivo é identificar alunos com maior probabilidade de cancelar a matrícula, permitindo que a academia tome ações preventivas para aumentar a retenção de clientes.

---

## 🎯 Problema de Negócio

A perda de alunos gera impacto direto na receita das academias.

Utilizando Machine Learning, é possível identificar padrões de comportamento que indicam risco de cancelamento e auxiliar na tomada de decisões.

---

## 📊 Dataset

Foi utilizado um dataset simulado com 100 registros contendo informações como:

* Idade
* Tipo de plano
* Tempo de matrícula
* Frequência semanal
* Faltas no mês
* Histórico de pagamento
* Valor da mensalidade
* Avaliação de satisfação

### Variável Alvo

**cancelou**

* 0 = Não cancelou
* 1 = Cancelou

---

## 🔍 Análise Exploratória (EDA)

Durante a análise foram identificados alguns padrões importantes:

* Alunos que frequentam menos a academia apresentam maior taxa de cancelamento.
* Clientes com pagamentos atrasados possuem maior probabilidade de cancelar.
* Baixos níveis de satisfação estão relacionados ao churn.
* O número de faltas mensais influencia diretamente o cancelamento.

---

## 🤖 Modelos Utilizados

### Regressão Logística

Modelo utilizado para prever o cancelamento de novos alunos.

### Random Forest

Modelo utilizado para classificação e análise de importância das variáveis.

---

## 📈 Avaliação do Modelo

Métricas utilizadas:

* Accuracy
* Precision
* Recall
* F1-Score

Resultados obtidos:

### Classe 1 (Cancelou)

* Precision: 60%
* Recall: 75%
* F1-Score: 67%

### Classe 0 (Não Cancelou)

* Precision: 80%
* Recall: 67%
* F1-Score: 73%

---

## 📌 Principais Variáveis

Segundo o Random Forest, as variáveis mais importantes foram:

1. Frequência semanal
2. Faltas no mês
3. Pagamento atrasado

Esses fatores demonstraram maior influência na previsão de cancelamento.

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 🚀 Possíveis Melhorias

* Aumentar o volume do dataset.
* Testar outros algoritmos de Machine Learning.
* Criar dashboard interativo no Power BI.
* Desenvolver API para previsão em tempo real.
* Realizar otimização de hiperparâmetros.

---

## 👨‍💻 Autor

Giovanni Nazarko

Estudante de Ciência de Dados e Inteligência Artificial, com foco em Machine Learning, Análise de Dados e Business Intelligence.
