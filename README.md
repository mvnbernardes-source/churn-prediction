# Previsão de Churn de Clientes

Projeto de Ciência de Dados com foco em análise exploratória e modelagem preditiva
para identificar clientes com maior probabilidade de churn.

## Objetivo
Analisar o comportamento dos clientes e desenvolver um modelo preditivo capaz
de identificar padrões associados ao churn.

## Tecnologias
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Modelos Utilizados
- Regressão Logística
- Random Forest

## Métrica
- ROC AUC para avaliação do desempenho dos modelos

## Conclusão
Embora a Regressão Logística tenha apresentado um valor de ROC AUC ligeiramente maior, o modelo de Random Forest foi escolhido por ser mais flexível e capaz de lidar melhor com relações não lineares presentes nos dados. As diferenças entre as métricas foram pequenas e não foram consideradas decisivas. Os resultados obtidos mostram os desafios do problema de risco de crédito, especialmente devido ao desbalanceamento das classes, e indicam que modelos mais simples podem ter limitações quando aplicados a dados reais.
