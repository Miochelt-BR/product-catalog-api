# product-catalog-api

# Cadastro de Produtos

Este é um projeto de cadastro de produtos desenvolvido em Python, que oferece uma API RESTful para realizar operações como cadastro, pesquisa e atualização de produtos, além de permitir o processamento assíncrono de arquivos CSV para cadastro em lote.

## Funcionalidades

- Cadastro de produto com código único, título e preço.
- Pesquisa de produto por código.
- Pesquisa de produtos por título com paginação.
- Atualização de preço do produto.
- Cadastro de produtos a partir de arquivos CSV.

## Tecnologias Utilizadas

- Python
- Flask (para a API)
- Redis (para a fila de mensagens)
- PostgreSQL (ou MongoDB)
- Docker (opcional)

## Estrutura do Projeto

- `api/`: Contém o código da API RESTful.
- `worker/`: Contém o código do trabalhador para processamento assíncrono de arquivos CSV.
- `db/`: Contém os modelos de dados e a configuração do banco de dados.
- `tests/`: Contém os testes unitários e de integração.
- `config.py`: Arquivo de configuração com as variáveis de ambiente.
- `.env`: Arquivo para definir as variáveis de ambiente.
- `requirements.txt`: Lista de dependências do projeto.

## Instalação e Execução

1. Clone o repositório:
git clone <URL_do_seu_repositório>
cd cadastro-produtos


2. Instale as dependências:
pip install -r requirements.txt

3. Configure as variáveis de ambiente no arquivo `.env`.

4. Execute a aplicação:
