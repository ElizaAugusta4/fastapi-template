# Template FastAPI

Este repositório é um exemplo de estrutura recomendada para projetos Python usando FastAPI. Aqui, utilizamos o `fastapi` para construir uma aplicação web e o `pytest` para rodar os testes.

Para um tutorial mais detalhado, veja nosso [tutorial de FastAPI](https://code.visualstudio.com/docs/python/tutorial-fastapi).

O código deste repositório segue as diretrizes de estilo Python conforme a [PEP 8](https://peps.python.org/pep-0008/).

## Como configurar

Este projeto utiliza Dev Containers. Para aproveitar essa configuração, certifique-se de ter o [Docker instalado](https://www.docker.com/products/docker-desktop).

Recomendamos as seguintes extensões do VS Code para facilitar o desenvolvimento:

- [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Python Debugger](https://marketplace.visualstudio.com/items?itemName=ms-python.debugpy)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) 

Além das extensões, algumas configurações do VS Code são úteis para o desenvolvimento. No editor de configurações (`Ctrl+,`), procure e ative:

- Python > Analysis > **Type Checking Mode**: `basic`
- Python > Analysis > Inlay Hints: **Function Return Types**: `enable`
- Python > Analysis > Inlay Hints: **Variable Types**: `enable`

## Como rodar o projeto

- Abra a pasta do projeto no VS Code (**Arquivo > Abrir Pasta...**)
- Abra a Paleta de Comandos (**Exibir > Paleta de Comandos...**) e execute o comando **Dev Container: Reabrir no Container**
- Rode a aplicação usando a visualização de Execução e Depuração ou pressionando `F5`
- `Ctrl + clique` na URL exibida no terminal para abrir a aplicação rodando
- Teste a API acessando a URL `/docs` para visualizar a interface Swagger UI
- Configure seus testes Python no Painel de Testes ou executando o comando **Python: Configurar Testes** na Paleta de Comandos
- Rode os testes no Painel de Testes ou clicando no botão de Play ao lado dos testes individuais no arquivo `test_main.py`