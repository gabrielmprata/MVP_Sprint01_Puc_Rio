# MVP_Sprint01_Puc_Rio
# Trabalho de elaboração de MVP (Minimum Viable Product)
A malha rodoviária é a principal forma de locomoção do país no que tange o deslocamento de pessoas, produtos, matérias primas, alimentos e combustível a curtas e longas distâncias.

Este trabalho visa mostrar através dos dados abertos disponibilizados pela Polícia Rodoviária Federal, dentre os 70.000 Km de rodovias onde atua, o impacto dos acidentes de trânsito e sua letalidade nas rodovias federais, tendo como período analisado o ano de 2020.

O Brasil é o terceiro país com mais mortes no trânsito, ficando atrás apenas da Índia e da China segundo o relatório Global Status Report on Road Safety da Organização Mundial de Saúde (OMS).

Cerca de 82% dos acidentes de trânsito nas rodovias federais brasileiras, são com vítimas, tendo em vista esse grande percentual de vítimas, nesse estudo, queremos entender os fatores que contribuem para os acidentes acontecerem.

## Coleta de dados:
https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes
>
Dataset: Agrupado por pessoa, 2019 e 2020
>  
## Tipo de problema:
>
Classificação, algoritmos de aprendizado de máquina supervisionado
>  

## Evaluation Metric
  Accuracy Score
>
## Comparative Analysis of Models
| Algorithm           | Mean Accuracy|
|---------------------|--------------|
| XGBoost             |    83,81%    |
>
## 5-Ws,
>
(Why?) Por que esse problema é importante?
>
Alto índice de acidentes com vítimas nas rodovias federais.
>
(Who?) De quem são os dados analisados? 
>
Dados abertos do Governo Brasileiro, disponibilizado pela Policia Rodoviária Federal.
>
(What?): Quais os objetivos com essa análise? O que iremos analisar? 
>
Analisar o comportamento dos acidentes em rodovias federais e o estado das vítimas.
>
(Where?): Trata dos aspectos geográficos e logísticos de sua análise.
>
Dentre os 70.000 Km de rodovias federais onde atua a PRF.
>
(When?): Qual o período está sendo analisado? 
>
Está sendo analisado 2019 e 2020.
>
## Tool, Libraries & Frameworks used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Plotly Express
- Folium
- Scikit-Learn
- XGBoost
- Scipy Stats Bernoulli
- Missingno
