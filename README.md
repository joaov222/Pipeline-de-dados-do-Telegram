# Pipeline-de-dados-do-Telegram

Neste projeto, desenvolvi um processo de ETL (Extração, Transformação e Carregamento) para um grupo no Telegram. O objetivo foi extrair as mensagens enviadas nesse grupo por meio de uma API, transformar os dados obtidos utilizando uma função Lambda na AWS e carregar essas informações em um formato adequado para análise no AWS Athena, que utiliza SQL.

Passo a passo do projeto:

Passo 1: Coleta de dados realizada a partir da API do Telegram para extrair mensagens de um grupo específico.

Passo 2: Processamento dos dados utilizando uma função Lambda na AWS para transformar as mensagens em um formato estruturado.

Passo 3: Armazenamento dos dados transformados em um formato compatível com SQL no AWS S3, preparado para análise.

Passo 4: Configuração do AWS Athena para consultar os dados armazenados e realizar análises SQL.
