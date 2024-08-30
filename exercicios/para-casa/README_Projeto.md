PROJETO GUIADO II

Análise de Dados de Voos

Este projeto realiza a análise de dados de voos a partir de um arquivo CSV. 
O dataset utilizado neste projeto contém informações sobre voos, incluindo datas de partida e chegada, aeroportos, número de paradas, e preços das passagens. Esses dados foram escolhidos por diversas razões:

Compreender o custo das passagens e como ele varia com base em diferentes fatores (como conexões e aeroportos) é extremamente relevante para consumidores e para a indústria de aviação. 
Analisar essas variáveis pode fornecer insights valiosos tanto para passageiros quanto para empresas aéreas.


REQUISITOS

- Python
- Bibliotecas:
  - `pandas`
  - `matplotlib`
  - `scipy`
  - `seaborn`
  - `sqlite3`
  - `ttest_ind`

DESCRIÇÃO

O código lê um arquivo CSV contendo dados sobre voos e realiza as seguintes operações:
1. Leitura e Exibição dos Dados**: Carrega os dados e exibe as primeiras linhas.
2. Análise de Dados: Verifica a presença de valores nulos e estatísticas descritivas dos dados.
3. Formatação de Datas: Converte colunas de datas para o formato adequado.
4. Remoção de Duplicatas: Identifica e remove linhas duplicadas.
5. Renomeação de Colunas: Renomeia colunas para uma versão mais amigável em português.
6. Exportação dos Dados Tratados: Salva o DataFrame tratado em um novo arquivo CSV.
7. Visualização de Dados: Gera gráficos para visualização de dados, incluindo contagem de voos por aeroporto e custos de passagens por companhia aérea.
Gráfico de barras da contagem de voos por aeroporto.
Gráfico de barras dos custos das passagens por companhia aérea.
8. Teste de Hipóteses: Realiza um teste T para comparar os preços de passagens com e sem conexão.
Gráfico de histograma comparando preços de passagens com e sem conexão.
rejeitamos a hipótese nula, indicando que há uma diferença significativa entre os preços das passagens sem conexão e com conexão.

9. Análise SQL: Realiza uma consulta SQL para analisar os preços das passagens por cabine para a companhia United Airlines.




