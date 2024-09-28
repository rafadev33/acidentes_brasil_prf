# acidentes_brasil_prf
Análise dos dados disponíveis no Portal Gov.br acerca dos acidentes de trânsito registrados pela Polícia Rodoviária Federal.

Esse trabalho objetivou analisar os dados registrados pela Polícia Rodoviária Federal (PRF) com todas as causas e tipos de acidentes, disponíveis em https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf.

Após baixado o arquivo csv, iniciou-se a análise e o tratamento dos dados ali contidos com o Pandas. Retiramos as linhas que continham dados nulos para podermos ter uma visão completa de todos os registros.
Tratamos os valores de números que estavam registrados como str transformando-os para valores númericos.
Tratamos também valores numéricos para str, como no caso dos meses que estavam registrados com números de 1 a 7, com seus respectivos nomes.

Depois de realizados os devidos tratamentos, passamos a cruzar os dados para obter informações sobre os acidentes ocorridos no Brasil. Dentre os dados que analisamos podemos destacar que:

Ocorreram cerca de 275 mil acidentes nas Rodovias Federais do Brasil (sem levar em conta os registros que possuem dados nulos, o que elevaria o número total de acidentes para 343 mil acidentes).

Desses 275 mil acidentes:

A - 146 mil resultaram em vítimas fatais com resultado morte;
B - 205 mil são do gênero masculino, cerca de 74,62%;
C - 70 mil são do gênero feminino, cerca de 25,33%;
D - Os cinco estados com maior número de acidentes são Minas Gerais, Paraná, Santa Catarina, Rio Grande do Sul e Bahia;
E - Domingo é o dia da semana com maior número de acidentes, seguido de sábado;
F - O mês de Julho teve o maior número de acidentes registrados;
G - A BR 116 é a Rodovia Federal com o maior número de mortos, totalizando 1991 vítimas fatais de acidentes de trânsito.
