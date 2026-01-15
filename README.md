# Modelagem e IA para Previsão de Produtividade do Milho (Mato Grosso)

Este repositório contém o Trabalho de Conclusão de Curso desenvolvido no Departamento de Engenharia de Biossistemas da **ESALQ/USP**. O projeto utiliza algoritmos de Machine Learning para prever a produtividade do milho segunda safra nos principais municípios produtores de Mato Grosso.

## 📋 Resumo do Projeto

O estudo propõe o desenvolvimento de algoritmos sofisticados de IA para antecipar variações na produção agrícola com base em dados espaço-temporais. Foram analisados indicadores climáticos e socioeconômicos nos meses anteriores ao início da safra para permitir uma tomada de decisão estratégica e eficaz.

## 🛠️ Metodologia

* **Fontes de Dados**: Dados meteorológicos obtidos via **NASAPower** e dados de produção/produtividade da plataforma **SIDRA (IBGE)**.


* **Modelos Avaliados**: Foram testados e comparados os algoritmos **Random Forest**, **XGBoost** e **LightGBM**.


* **Cenários**: A modelagem foi estruturada em quatro cenários distintos, variando a antecedência dos dados de entrada de 2 a 5 meses (Janeiro a Maio).


* **Pré-processamento**: Aplicação de técnicas de escalonamento como `MinMaxScaler`, `StandardScaler` e `RobustScaler`, além de otimização de hiperparâmetros via `GridSearchCV`.



## 🚀 Resultados

O algoritmo **LightGBM** apresentou o melhor desempenho no Cenário 1 (Jan-Mai) utilizando `MinMaxScaler` e `GridSearchCV`:

* **Coeficiente de Determinação ()**: 0,609.


* **Erro Médio Absoluto (MAE)**: 630,01 kg/ha.


* **Principais Preditores**: A produtividade histórica da safra anterior e a Evapotranspiração de Referência () foram as variáveis mais influentes.



## 👨‍🎓 Autor

* **Aluno**: Ulysses Chaves de Menezes Netto.


* **Orientador**: Prof. Dr. Fábio Ricardo Marin.


* **Instituição**: Escola Superior de Agricultura "Luiz de Queiroz" - USP.
