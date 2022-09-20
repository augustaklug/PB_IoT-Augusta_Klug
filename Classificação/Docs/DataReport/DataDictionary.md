# Data Dictionary

## Resumo dos dados: 
Dados experimentais utilizados para classificação binária (ocupação do ambiente) a partir da temperatura, umidade, 
luz e CO2. Dados de campo para a ocupação real foram obtidos a partir de fotos com *timestamp* que foram tiradas a cada minuto.

## Período dos dados:
2015-02-02 14:19:00 a 2015-02-18 09:19:00

## Taxa de amostragem:
uma amostra por minuto

## Informações das colunas:
* **date**: data registrada em ano-mês-dia hora:minuto:segundo
* **Temperature**: temperatura, em Celsius
* **Humidity**: umidade relativa do ar, em %
* **Light**: iluminação, em Lux
* **CO2**: concentração de dióxido de carbono (CO2), em ppm
* **HumidityRatio**: razão de uidade, quantidade derivada da temperatura e umidade relativa, em kg-vapor de água/kg-ar
* **Occupancy**: 0 para não ocupado, 1 para ocupado

## Fonte dos dados:
[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+)<br>
**Autor:** Luis Candanedo, luismiguel.candanedoibarra '@' umons.ac.be, UMONS.
