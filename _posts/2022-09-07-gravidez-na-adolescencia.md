---
layout: post
title: "Gravidez na Adolescência e Desigualdade Social"
date: 2022-09-07
excerpt: "Trabalho desenvolvido para a disciplina de Análise de Dados no R"
tags: [portfolio, data science, statistics, R]
feature: https://i.imgur.com/C0JIpza.png
comments: true
---

#### Trabalho desenvolvido para a disciplina de "Análise de Dados no R" que cursei durante meu bacharelado na Universidade Federal de Goiás. 

# Gravidez na Adolescência e Desigualdade Social

## Introdução

A adolescência corresponde a faixa etária dos 10 aos 19 anos. Esse período
compreende importantes mudanças físicas, psicológicas e comportamentais (Blakemore,
2018). Uma gravidez realizada nesse período apresenta diversas consequências sociais
negativas na vida das jovens mães, como evasão escolar e dificuldade de inserção no
mercado de trabalho. Além disso, mães adolescentes enfrentam maior risco de eclâmpsia,
infecções sistêmicas, anemia, diabetes gestacional e outros distúrbios( Azevedo et al., 2015).
A incidência de gravidez nessa faixa etária é maior em populações mais vulneráveis(Michelazzo et al., 2004). Neste trabalho eu utilizei dados do Brasil para avaliar a correlação entre o índice de Gini e a taxa de fecundidade de adolescentes, avaliada por número de gravidez a cada 1000 mulheres de 15 a 19 anos.

## Materiais e Métodos

Os dados analisados são de autoria do Banco Mundial e foram acessados pela plataforma online de acesso livre (https://data.worldbank.org/).Foram considerados os dados de 1985 a 2020, sendo removido das análises anos que possuíram algum valor faltante. A variável que correspondente a gravidez na adolescência diz respeito a dados anuais do número de gravidez por 1000 mulheres com idade de 15 a 19 anos. A variável escolhida para avaliar a desigualdade social foi o Índice de Gini, variando de 0 a 100. A análise de correlação foi feita calculando o coeficiente de Pearson e o p-valor para esse resultado.
Todas as análises foram realizadas no software R.

## Resultados

O ano que apresentou a maior taxa de fecundidade foi 1997, cujo valor foi 84.26. A menor taxa, 55.43, foi atingida em 2020, último ano considerado nas análises (Figura 1) . No geral, os dados apontam para uma tendência de queda na taxa de fecundidade e no índice de Gini.
As duas variáveis se mostraram altamente correlacionadas, com um coeficiente de Pearson de 𝑝 = 0.856 e um 𝑝−𝑣𝑎𝑙𝑜𝑟 = 4.191^ −10 (Figura 2).

<figure>
	<a href="https://i.imgur.com/kf1Qwb6.png"><img src="https://i.imgur.com/kf1Qwb6.png"></a>
	<figcaption><a href="https://i.imgur.com/kf1Qwb6.png" title="Figura 1.">Distribuição dos valores da Taxa de Fecundidade( em azul) e do índice de Gini (em vermelho) ao longo dos anos</a>.</figcaption>
</figure>

<figure>
	<a href="https://i.imgur.com/hBTvC7p.png"><img src="https://i.imgur.com/hBTvC7p.png"></a>
	<figcaption><a href="https://i.imgur.com/hBTvC7p.png" title="Figura 2.">Correlação entre a Taxa de Fecundidade, representada no eixo X e o Índice de Gini,representado no eixo Y</a>.</figcaption>
</figure>


## Discussão e Conclusão

Fica evidente a correlação entre a taxa de gravidez na adolescência e a desigualdade social
medida através do índice de Gini. Em trabalho recente, Monteiro et al.,( 2021) encontraram uma redução na taxa de gravidez na adolescência ao longo dos anos no Brasil, além de uma forte correlação entre essa taxa e o Índice de Desenvolvimento Humano (IDH) em regiões brasileiras. Os resultados encontrados aqui podem complementar os encontrados por Monteiro et al.,( 2021) uma vez que o IDH não incorpora a desigualdade em seu cálculo.

## Referências
AZEVEDO, W. F. DE et al. Complications in adolescent pregnancy: systematic review of the literature.
Einstein (São Paulo), v. 13, n. 4, p. 618–626, 9 jun. 2015.
BLAKEMORE, S.-J. Development of the Social Brain during Adolescence. Quarterly Journal of
Experimental Psychology, v. 61, n. 1, p. 40–49, jan. 2008.
LESSER, J.; ESCOTO-LLOYD, S. HEALTH-RELATED PROBLEMS IN A VULNERABLE POPULATION.
Nursing Clinics of North America, v. 34, n. 2, p. 289–299, jun. 1999.
MICHELAZZO, D. et al. Indicadores sociais de grávidas adolescentes: estudo caso-controle. Revista
Brasileira de Ginecologia e Obstetrícia, v. 26, n. 8, p. 633–639, set. 2004.
MONTEIRO, D. L. M. et al. Trends in teenage pregnancy in Brazil in the last 20 years (2000-2019).
Revista da Associação Médica Brasileira, v. 67, n. 5, p. 759–765, jun. 2021.
WORLD. Adolescent pregnancy. Disponível em:
<https://www.who.int/news-room/fact-sheets/detail/adolescent-pregnancy>. Acesso em: 7 set. 2022