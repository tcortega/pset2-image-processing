# Problem Set 2: MIT 6009 Lab1 - Processamento de Imagem

Projeto feito como requisito avaliativo da disciplina de *Linguagens de Programação* na Universidade Vila Velha.

## Nota para o professor

Todas questões perguntadas no pdf original estão respondidas no arquivo [Respostas Questionario.pdf](Respostas%20Questionario.pdf).   
E os arquivos nos quais foram pedido transformações, são as imagens que se encontram na raiz do repositório.

## Pré-requisitos para execução
- Python (Testado apenas na versão 3.10.6)
- Tkinter

## Preparando o projeto

Para realizar a preparação do projeto, primeiro é necessário instalar as dependências:

```bash
pip install -r requirements.txt
```

Após isso, caso esteja em um ambiente linux, é possível que não tenha o tkinter instalado para o python3. Para isso, 
recomenda-se verificar a existência, e caso não exista, instalar utilizando o comando a baixo:

```bash
sudo apt-get install python3-tk
```

## Executando o projeto

A execução do projeto consiste basicamente em executar os testes unitários, descritos no arquivo [test.py](test.py). Então basta
digitar:

```bash
$ python3 test.py
```
ou dependendo da sua instalação do python
```bash
$ py test.py
```
