# Pipeline de ETL de Dicas de Investimento


## Descrição do Projeto
O intuito do projeto é fazer uma prática de ETL e através do uso da API do Chatgpt.A ideia é gerar dados a respeito de tipos de investimentos que os usuários podem se dedicar por meio de características fornecidas em um arquivo `SDW23.csv` dessa forma, apos a leitura do arquivo, esses dados são guardados e usados para que a API gere uma informação útil, sendo a classificação do tipo de investidor: conservador, moderado, arrojado e dicas sobre investimento em renda variável e renda fixa.

### Definição de ETL
ETL é uma sigla que representa um processo importante no campo da informática e da análise de dados. Ela significa:

1.Extração (Extraction): Nesta fase, os dados são coletados de várias fontes diferentes, que podem incluir bancos de dados, sistemas de armazenamento de arquivos, aplicativos da web e outras fontes de dados. O objetivo é reunir todas as informações necessárias em um local centralizado para análise.

2.Transformação (Transformation): Após a extração dos dados, eles são transformados em um formato adequado para análise. Isso pode envolver a limpeza dos dados, a remoção de informações duplicadas ou inconsistentes, a conversão de tipos de dados e a aplicação de regras de negócios para preparar os dados para uso.

3.Carga (Load): Nesta etapa, os dados transformados são carregados em um sistema de destino, como um data warehouse, um banco de dados relacional ou uma plataforma de análise. Isso permite que os dados sejam facilmente acessados e consultados por analistas de dados, cientistas de dados e outros profissionais que precisam realizar análises ou criar relatórios.

### Pré-requesitos para rodar o projeto:

- Python3 instalado.
- pip instalado.
- Biblioteca da open ai: `pip install openai`
- Ter uma API key que você pode gerar ao criar sua conta vinculada a [OpenAI](https://platform.openai.com/account/api-keys).
