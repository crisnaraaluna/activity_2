# Projeto de Processamento de Dados

## Objetivo

Este projeto visa processar e limpar dados de voos, realizar engenharia de características e armazenar os dados processados em um banco de dados SQLite.

## Organização dos Arquivos

* `utils.py`: Contém funções utilitárias para processamento e validação de dados.
* `app.py`: Contém funções principais para limpeza de dados, engenharia de características e interação com o banco de dados SQLite.
* `requirements.txt`: Lista de dependências do projet
* `README.md`: Documentação do projeto.

## Como Executar

1. Instale as dependências:
pip install -r requirements.txt

2. Configure as variáveis de ambiente `META_PATH` e `DATA_PATH` com os caminhos para o arquivo de metadados e os dados.

3. Execute o script principal:
python app.py

## Logs

Os logs do processo são salvos no arquivo `data/flights_pipe_log.log`.