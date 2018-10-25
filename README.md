# ml-notebooks
Notebooks de exercícios para a disciplina de Aprendizado de Máquina. 


## Entrega dos notebooks

Todos os notebooks de exercícios devem estar resolvidos até o dia **24/11/2018**.

Os notebooks a serem coletados devem ser os que estão disponibilizados no **seu repositório. Não utilize os notebooks que estão no repositório ml-notebooks, 
pois podem haver diferenças no ID dos boxes, invalidando a correção dos exercícios no autograder.**

### Como será feita a coleta dos notebooks?

Executaremos um script que percorrerá **todos os repositórios dos alunos a meia noite desta data**. Os notebooks serão copiados para a máquina dos professores, e então o autograder será executado. Portanto, **certifique-se de fazer um push para o seu repositório remoto antes da data limite de coleta.** Além disso, você não precisa fazer mais nada. **Não envie seus notebooks por e-mail após esta data, pois os mesmos não serão considerados.**

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