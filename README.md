### Projeto 4: Análise de Desempenho de Atletas por País em Olimpíadas

#### Visão Geral

Este projeto realiza uma análise descritiva (EDA) de um conjunto de dados sobre os Jogos Olímpicos para identificar padrões de desempenho de atletas e países ao longo do tempo. O foco é em estatísticas e correlações para extrair insights valiosos do dataset.

#### Objetivos do Projeto

* Limpar e tratar dados brutos para torná-los consistentes e utilizáveis.
* Identificar os países com o melhor desempenho geral em termos de medalhas conquistadas.
* Analisar a correlação entre o número de atletas e o total de medalhas por país.
* Mostrar a evolução do desempenho de um país (Brasil) ao longo de diferentes edições das Olimpíadas.

#### Metodologia

A análise seguiu os seguintes passos:

1.  **Limpeza e Filtragem de Dados:** O dataset foi carregado e filtrado para incluir apenas os registros de atletas que ganharam medalhas, removendo os valores ausentes na coluna medalha.
2.  **Análise de Desempenho por País:** Foi realizada uma contagem das medalhas por país para identificar os líderes em termos de premiações.
3.  **Análise de Correlação:** A correlação entre o número de atletas e o número de medalhas por país foi calculada para entender a relação entre essas duas variáveis.
4.  **Análise Temporal:** Foi feita uma análise do desempenho do Brasil ao longo dos tempo, contando as medalhas por ano.

#### **Resultados da Análise**

##### **Países com Melhor Desempenho (Total de Medalhas)**

A tabela mostra os 10 países que conquistaram o maior número de medalhas em todas as edições dos jogos incluídas no conjunto de dados.

| País | Total de Medalhas |
|:---|:---|
| USA | 1943 |
| Russia | 1148 |
| Germany | 1032 |
| Australia | 832 |
| China | 782 |
| Canada | 662 |
| Italy | 536 |
| UK | 514 |
| France | 513 |
| Netherlands | 482 |

##### **Correlação entre Medalhas e Atletas**

* A correlação entre a quantidade de medalhas e o número de atletas por país é de **1.00**, indicando uma relação linear e positiva muito forte entre as duas variáveis.

##### **Desempenho do Brasil ao Longo do Tempo**

A tabela a seguir detalha o desempenho do Brasil em termos de total de medalhas por ano, destacando como o número de medalhas variou em cada edição.

| Ano | Total de Medalhas |
|:---|:---|
| 1996 | 63 |
| 2000 | 48 |
| 2004 | 40 |
| 2008 | 78 |
| 2012 | 59 |
| 2016 | 50 |
