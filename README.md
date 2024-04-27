
![bras_83x140_reduzido](https://github.com/gabrielmprata/MVP_Sprint01_Puc_Rio/assets/119508139/4880e33f-47b7-4b75-8a84-bb2d57a8c5f2) 
**Pontifícia Universidade Católica do Rio de Janeiro**

#  📚 Trabalho de elaboração de MVP 📖
#### Curso de Pós Graduação *Ciência de Dados e Analytics*
#### Aluno: Gabriel Prata
#### Disciplina: Análise Exploratória e Pré Processamento de Dados
#### MVP Sprint01 Puc Rio
>
[![Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gabrielmprata/MVP_Sprint01_Puc_Rio/blob/main/MVP_Analise_de_Dados_e_boas_praticas.ipynb)
>
# 1. Definição do problema
A malha rodoviária é a principal forma de locomoção do país no que tange o deslocamento de pessoas, produtos, matérias primas, alimentos e combustível a curtas e longas distâncias.

Este trabalho visa mostrar através dos dados abertos disponibilizados pela Polícia Rodoviária Federal, dentre os 70.000 Km de rodovias onde atua, o impacto dos acidentes de trânsito e sua letalidade nas rodovias federais, tendo como período analisado o ano de 2020.

O Brasil é o terceiro país com mais mortes no trânsito, ficando atrás apenas da Índia e da China segundo o relatório Global Status Report on Road Safety da Organização Mundial de Saúde (OMS).

Cerca de 82% dos acidentes de trânsito nas rodovias federais brasileiras, são com vítimas, tendo em vista esse grande percentual de vítimas, nesse estudo, queremos entender os fatores que contribuem para os acidentes acontecerem.

# 2. Coleta de Dados
>
Os dados foram coletados do sítio da Polícia Rodoviária Federal.
<img align="left" width="80" height="94" src="https://github.com/gabrielmprata/MVP_Sprint01_Puc_Rio/assets/119508139/f9646e84-d274-406b-9a7a-12add19acb07">
>
https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes
>
Dataset: Agrupado por pessoa, 2019 e 2020
<br><br>
# 3. Tipo de problema:
>
Classificação, algoritmos de aprendizado de máquina supervisionado
>
**5-Ws**
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
<br><br>
# 4. Ferramentas utilizadas
<img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg" width="40" height="40"/>   <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/plotly/plotly-original-wordmark.svg" width="40" height="40"/>  <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40"/> <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original-wordmark.svg" width="40" height="40"/> <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original-wordmark.svg" width="40" height="40"/>
<br><br>
# 5. Evaluation Metric
  Accuracy Score
>
## Comparative Analysis of Models
| Algorithm           | Mean Accuracy|
|---------------------|--------------|
| XGBoost             |    83,81%    |
>
<br><br>
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
