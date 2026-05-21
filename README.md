# Relatório Final de Insights: Estratégia de Retenção PicPay

## 📌 Sumário Executivo
Este projeto consistiu no desenvolvimento de um ecossistema de análise preditiva para combater o Churn. Utilizando técnicas avançadas de Ciência de Dados e Visualização, transformando dados brutos em um painel estratégico capaz de orientar a tomada de decisão da alta gestão.

---

## 🚀 Evolução do Projeto (Versão 2.0)
Após a validação inicial do modelo, o projeto passou por uma esteira de **Melhoria Contínua** baseada em revisões técnicas de negócios para problemas de Churn desbalanceado. Foram implementadas as seguintes evoluções:

1. **Matriz de Confusão Visual:** Implementada para avaliar a distribuição de acertos entre clientes retidos e em evasão, mitigando o risco de falsos negativos.
2. **F1-Score como Métrica Primária:** Como bases de Churn são historicamente desbalanceadas, a análise foi blindada utilizando o F1-Score (média harmônica entre precisão e recall) na classe de evasão, garantindo a real eficácia do modelo em identificar quem vai deixar a plataforma.

---

## 📊 Desempenho do Modelo Preditivo
Para prever o comportamento dos clientes, o algoritmo Random Forest apresentou resultados consolidados e validados:

* **Acurácia Geral:** 86,45% (Alta capacidade de classificação geral).
* **F1-Score (Classe Churn):** [0.57] — Esta métrica garante que o modelo é estatisticamente assertivo em detectar a evasão em uma base desbalanceada.
* **Precisão:** 75% (Quando o modelo sinaliza um risco de saída, ele está correto na grande maioria das vezes, otimizando o orçamento de marketing de retenção).

[[Link para o Dashboard Interativo aqui](https://datastudio.google.com/s/qmsBnA-osJM)] 
