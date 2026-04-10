# Projeto_IA

Sistema de Recomendação de Filmes e Séries
Este projeto foi desenvolvido como Trabalho de Conclusão de Curso (TCC) do Bacharelado em Engenharia da Computação.
O sistema consiste em uma aplicação web que permite aos usuários avaliar filmes e séries, além de receber recomendações personalizadas com base em suas preferências, utilizando conceitos de Machine Learning.

Funcionalidades
Cadastro de usuários
Avaliação de filmes e séries
Armazenamento de dados em banco de dados
Sistema de recomendação personalizado
Consulta de conteúdos cadastrados
Interface para interação com o usuário

Tecnologias Utilizadas
Python
JavaScript
HTML / CSS
SQL
Biblioteca de Machine Learning Scikit-learn

Como funciona a recomendação
O sistema utiliza dados de avaliações dos usuários para identificar padrões de preferência.
A partir dessas informações, são aplicadas técnicas de Machine Learning para sugerir novos filmes e séries com maior probabilidade de interesse, considerando o histórico e comportamento do usuário.

Objetivo do Projeto
Desenvolver uma solução capaz de demonstrar, na prática, a aplicação de conceitos de:
Desenvolvimento de software
Estruturas de dados
Banco de dados
Inteligência Artificial
Machine Learning

Como executar o projeto
Clonar o repositório
Instalar dependências
Executar a aplicação

Melhorias Futuras
Aprimorar o algoritmo de recomendação
Melhorar a interface do usuário
Implementar autenticação mais robusta
Expandir a base de dados

## Project Setup
Creation of Virtual Environments
```sh
pip install virtualenv
```
```sh
py -m venv venv
```
Windows PowerShell
```sh
venv\Scripts\Activate.ps1
```

Linux PowerShell
```sh
source venv/bin/activate
```

Windows cmd.exe
```sh
venv\Scripts\activate.bat
```

Run requirement.txt
```sh
pip install -r requirements.txt
```

Run Project
```sh
cd msa_back 
```

```sh
py manage.py migrate 
```

```sh
py manage.py runserver 
```
