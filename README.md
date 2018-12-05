# ml-notebooks
Notebooks de exercícios para a disciplina de Aprendizado de Máquina. 

## Pesos dos exercícios


|                 | Tarefa 1 | Tarefa 2 | Tarefa 3 | Tarefa 4 | Tarefa 5 | Tarefa 6 | Tarefa 7 |
|:---------------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
| preprocessing   |   1.5    |    2     |    2     |    1.5   |     1    |    1     |     1    |
| neural networks |    1     |    1     |   1.5    |    1.5   |     1    |    0     |     4    |


## Criação do ambiente virtual 
Para fazer os exercícios, é necessário criar um ambiente virtual no Anaconda:

1. Instale a distribuição Anaconda do Python 3: [link](https://www.anaconda.com/download/#linux)
2. Crie um novo interpretador Python:

```
conda create --name py3 python=3
```
3. Ative o ambiente virtual 

no Linux:
```
source activate py3
```
no Windows:
```
activate py3
```

4. Instale os pacotes necessários usando o arquivo ```requirements.txt```:

```
conda install --file requirements.txt
```

### Execução dos exercícios

Na pasta raiz, ative o ambiente virtual recém criado:

no Linux:
```
source activate py3
```
no Windows:
```
activate py3
```

Inicie o servidor Jupyter:

```
jupyter notebook
```

Navegue até o notebook desejado.

Não se esqueça de salvar as modificações feitas no notebook com o comando ```CTRL + S```. 
