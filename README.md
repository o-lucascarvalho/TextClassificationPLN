# TextClassificationPLN
Projeto de conclusão de disciplina de PLN do curso de Pós Graduação em Ciência de Dados pela PUCPR

Objetivo do projeto era a aplicação de técnicas de pré processamento dos dados para criação de um modelo capaz de realizar a classificação entre Positivo, Negativo e Neutro. 
No arquivo inicial 2000_textos.csv, existem mais emoções pré rotuladas, porém a especificação do projeto exigia a criação de um De/Para separando algumas emoções como Positiva, outras como negaticas e o restante como Neutro.

Também foi avaliada uma ação de balanceamento dos dados, neste projeto, foi utilizado em primeiro momento o Oversampling e, após encontrar um certo vicio na classe positiva devido a forma de balanceamento aplicada, foi aplicado o método SMOTE, que nos trouxe um resultado melhor. 
