#  Análise e Predição de Desempenho Acadêmico com Aprendizado de Máquina Supervisionado: Uma Abordagem com Scikit-Learn`
## Faculdade de Computação e Informática (FCI)`
### Universidade Presbiteriana Mackenzie – São Paulo, SP – Brasil`

## 1. Título
Análise e Predição de Desempenho Acadêmico com Aprendizado de Máquina Supervisionado: Uma Abordagem com Scikit-Learn.

## 2. Integrantes
* Gabriel Maciel Figueiredo Constantino da Silva.
* [gabriel.maciel.2002@gmail.com](mailto:gabriel.maciel.2002@gmail.com)
* 104192921

## 3. Resumo
Este projeto tem como foco a aplicação de técnicas de Inteligência Artificial para prever o desempenho escolar de estudantes com base em dados reais de comportamento, contexto socioeconômico e desempenho acadêmico. Utilizando a biblioteca Scikit-Learn, foi desenvolvido um modelo de classificação supervisionada para prever a aprovação final de alunos com base no "Student Performance Data Set", fornecido pela UCI Machine Learning Repository. Foram realizadas análises estatísticas, visualizações dos dados, avaliação de modelos e discussão ética sobre o uso de IA na educação. O modelo de Random Forest obteve resultados satisfatórios, com destaque para as variáveis mais relevantes no desempenho escolar.

## 4. Introdução
### A. Contextualização
A capacidade de prever o desempenho de estudantes com antecedência é essencial para intervenções pedagógicas mais eficazes. A Inteligência Artificial pode auxiliar no reconhecimento de padrões ocultos em dados escolares, contribuindo para a tomada de decisões educacionais mais assertivas.
### B. Justificativa
A educação é uma das áreas que mais se beneficiam da IA. O uso de algoritmos de aprendizado de máquina para identificar estudantes em risco de baixo desempenho pode permitir a aplicação de ações corretivas, melhorando o rendimento geral e reduzindo a evasão.
### C. Objetivo
O objetivo é desenvolver um modelo de classificação supervisionado capaz de prever se um aluno será aprovado ou reprovado ao final do período letivo, com base em atributos como métricas de participação, desempenho anterior e contexto pessoal.
### D. Opção do Projeto
Opção Framework: Utilização da biblioteca Scikit-Learn para aplicação de algoritmos de classificação supervisionada.

## 5. Descrição do Problema
A reprovação de estudantes pode ocorrer por diversos fatores, como baixa carga de estudo, problemas familiares, ou ausências. Ao tratar o desempenho como um problema de classificação binária (aprovado ou reprovado), é possível utilizar IA para prever com antecedência quais alunos estão em risco e aplicar estratégias de apoio. Esse tipo de solução é especialmente útil em ambientes educacionais que possuem grandes volumes de alunos, onde o acompanhamento individualizado é mais difícil.

## 6. Aspectos Éticos e Responsabilidade no uso da IA
Ao utilizar IA na educação, deve-se garantir a ética no tratamento dos dados. Isso inclui:
* Respeito à privacidade dos alunos
* Anonimização dos dados
* Ausência de vieses discriminatórios
* Transparência nos modelos aplicados
* Uso dos resultados para apoio pedagógico, e não como ferramenta punitiva
Além disso, deve-se garantir que professores e gestores compreendam como a IA está sendo utilizada e que tenham autonomia sobre a interpretação dos resultados.

## 7. Dataset, descrição, análise exploratória e preparação dos dados
Utilizou-se a base "student-mat.csv", contendo 395 registros com 33 atributos. Foram analisadas distribuições de notas, relações entre tempo de estudo, número de reprovações e absenteísmo com a nota final (G3). A variável G3 foi binarizada para indicar aprovação (1) ou reprovação (0). Os dados foram normalizados e categóricos codificados com LabelEncoder.

## 8. Metodologia e Resultados Esperados
Foi aplicada uma metodologia baseada em classificação supervisionada, com Random Forest como algoritmo principal. A escolha do modelo se deu por sua robustez frente a dados heterógenos e capacidade de lidar com dados categóricos. Espera-se obter acurácia acima de 75%, e identificar os principais fatores que influenciam o desempenho dos estudantes, como tempo de estudo, reprovações anteriores e apoio familiar.

## 9. Referências bibliográficas
1. UCI Machine Learning Repository. Student Performance Data Set. https://archive.ics.uci.edu/ml/datasets/student+performance
1. Scikit-Learn Documentation. https://scikit-learn.org/stable/
1. Géron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. O'Reilly Media.
1. Russell, S., & Norvig, P. (2013). Artificial Intelligence: A Modern Approach. Pearson.
1. Romero, C., & Ventura, S. (2020). Educational data mining and learning analytics: An updated survey. Wiley.
1. Baker, R. S. J. d. (2019). Challenges for the future of educational data mining. Journal of Educational Data Mining.
1. Selwyn, N. (2019). Should Robots Replace Teachers?. Polity Press.

## 10. Bibliografia
1. Koedinger, K. R., et al. (2015). Data mining and education. Wiley Interdisciplinary Reviews.
1. Moreno-Marcos, P. M., et al. (2019). Predicting learners' performance in MOOCs. Computers in Human Behavior.
1. Camelo, L. (2023). API do ChatGPT: como usar todo o poder da IA. Pluga Blog.
1. Zerbinatti, L. (2025). Conteúdo da disciplina de Inteligência Artificial. Universidade Presbiteriana Mackenzie.
