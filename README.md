# Análise de Dados das Eleições Municipais com PySpark
Este repositório contém um notebook Jupyter com uma análise de dados das eleições municipais de 2020 utilizando PySpark.

**Etapas do Desenvolvimento**
As principais etapas do desenvolvimento foram:
1. Configuração do ambiente Spark local no notebook
2. Carregamento dos dados de resultados das eleições e do perfil do eleitorado em dataframes Spark
3. Pré-processamento e seleção das colunas de interesse nos dataframes
4. Análises:
  * Encontrar o candidato a prefeito mais votado por município
  * Buscar informações de perfil predominante do eleitorado e percentual de votos por zona eleitoral
  * Identificar as zonas com maior número de abstenções/votos brancos e nulos
5. Geração de visualizações e insights
  
**Replicação**
Para replicar a análise, são necessários os seguintes passos:
1. Instalar as bibliotecas necessárias (PySpark, findspark, pandas, etc)
2. Baixar os dados de resultados das eleições e perfil do eleitorado
3. Configurar o ambiente Spark local no notebook
4. Carregar os dados em dataframes Spark
5. Executar as células de pré-processamento e análise
   
Os dados originais utilizados neste notebook estão disponíveis em:
Resultados: https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais
Perfil do Eleitorado: https://www.tse.jus.br/eleitor/estatisticas-de-eleitorado/perfil-do-eleitorado
