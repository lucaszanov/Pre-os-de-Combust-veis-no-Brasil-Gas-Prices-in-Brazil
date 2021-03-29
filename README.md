# Precos-de-Combustiveis-no-Brasil-Gas-Prices-in-Brazil | *Gas Prices in Brazil*

Preços dos combustíveis no Brasil entre os anos de 2004 e 2019 | *Gas Prices in Brazil from 2004 to 2019*

![download](https://user-images.githubusercontent.com/72801602/112895566-ae22e400-90b3-11eb-8196-4b53ff2b61cd.png)

# Entendimento do problema

A Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP) semanalmente reporta os valores de distribuição e revenda para combustíveis como gás, diesel e outros usados no transporte ao redor do país. Entre estes dados, encontram-se o número de postos avaliados, a região e estado, o preço médio de distribuição e revenda, juntamente aos mínimos e máximos, desvios, margem de revenda, entre outros.

O objetivo deste estudo, dessa forma, é analisar alguns pontos de interesse, como:

1. Como se dá a variação de preços dos combustíveis por região e estado do país;

2. Como foi a evolução temporal durante os anos de 2004 e 2019 nas médias de preço de distribuição e revenda;

3. Quais fatores estão correlacionados (preços, desvios, estados, etc);

4. Todos os produtos possuem preços próximos ou existem produtos com valores muito abaixo ou muito acima dos demais?

E, por fim, 

5. Construir um modelo via regressão linear que seja capaz de predizer o preço médio de distribuição dados estado, região, ano, produto e preço médio de revenda de interesse.

# Fonte

Como mencionado anteriormente, os conjuntos de dados são fornecidos pela ANP e regularmente atualizados com novos dados e novas informações. Estes dados podem ser consultados no link: http://www.anp.gov.br/precos-e-defesa-da-concorrencia/precos/levantamento-de-precos/serie-historica-do-levantamento-de-precos-e-de-margens-de-comercializacao-de-combustiveis. Para este estudo, foi utilizado o dataset disponibilizado no Kaggle por Matheus Eduardo Freitag em https://www.kaggle.com/matheusfreitag/gas-prices-in-brazil.
