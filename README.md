# Template FastAPI

Este repositório é um exemplo de estrutura recomendada para projetos Python usando FastAPI. Aqui, utilizei o `fastapi` para construir uma aplicação web e o `pytest` para rodar os testes. Além disso, adicionei uma pipeline para buildar a aplicação e enviar para AWS ECR.

O código deste repositório segue as diretrizes de estilo Python conforme a [PEP 8](https://peps.python.org/pep-0008/).

## Como rodar o projeto

- Abra a pasta do projeto no VS Code (**Arquivo > Abrir Pasta...**)
- Abra a Paleta de Comandos (**Exibir > Paleta de Comandos...**) e execute o comando **Dev Container: Reabrir no Container**
- Rode a aplicação usando a visualização de Execução e Depuração ou pressionando `F5`
- `Ctrl + clique` na URL exibida no terminal para abrir a aplicação rodando
- Teste a API acessando a URL `/docs` para visualizar a interface Swagger UI
- Configure seus testes Python no Painel de Testes ou executando o comando **Python: Configurar Testes** na Paleta de Comandos
- Rode os testes no Painel de Testes ou clicando no botão de Play ao lado dos testes individuais no arquivo `test_main.py`
