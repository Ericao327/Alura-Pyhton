# Sabor Express 🍽️

Aplicação de terminal para cadastro e gerenciamento de restaurantes, desenvolvida durante o curso [Python: crie sua primeira aplicação](https://cursos.alura.com.br/course/python-crie-sua-primeira-aplicacao), da Alura.

O projeto simula um pequeno sistema de back-office para um app de delivery, permitindo cadastrar restaurantes, listar os que já existem e alternar seu status entre ativo e inativo.

## Funcionalidades

O menu principal oferece as seguintes opções:

1. **Cadastrar restaurante** — registra um novo restaurante informando nome e categoria. Todo restaurante novo começa como inativo.
2. **Listar restaurantes** — exibe uma tabela com nome, categoria e status (ativado/desativado) de todos os restaurantes cadastrados.
3. **Alternar estado do restaurante** — busca um restaurante pelo nome e inverte seu status (de ativo para inativo ou vice-versa).
4. **Sair** — finaliza a aplicação.

## Como executar

Pré-requisito: Python 3.12 ou superior (o projeto usa f-strings com aspas simples aninhadas, suportadas a partir dessa versão).

```bash
python3 app.py
```

> **Observação:** o programa usa `os.system('clear')` para limpar o terminal entre as telas. Esse comando funciona em Linux e macOS; em Windows, pode ser necessário trocar `'clear'` por `'cls'` no código.

## Estrutura do projeto

```
sabor-express/
├── app.py                      # Aplicação principal (Sabor Express)
└── Exercícios de teste/         # Exercícios de prática do curso
    ├── Teste1.py                # Verifica se um número é par ou ímpar
    ├── Teste2.py                # Classifica idade em criança, adolescente ou adulto
    ├── Teste3.py                # Simulação simples de login com usuário/senha
    └── Teste4.py                # Identifica o quadrante de um ponto (x, y)
```

## Sobre os exercícios de teste

A pasta `Exercícios de teste` reúne pequenos scripts usados para praticar estruturas condicionais (`if`, `elif`, `else`) em Python, trabalhadas ao longo do curso:

- **Teste1.py**: lê um número e informa se ele é par ou ímpar.
- **Teste2.py**: lê uma idade e classifica a pessoa como criança, adolescente ou adulto.
- **Teste3.py**: simula uma verificação de login comparando usuário e senha digitados com valores fixos.
- **Teste4.py**: lê as coordenadas `x` e `y` de um ponto e indica em qual quadrante do plano cartesiano ele está.

## Conceitos praticados

- Estruturas condicionais (`if`, `elif`, `else`)
- Listas e dicionários
- Funções e organização de código
- Laços de repetição (`for`)
- Tratamento de exceções (`try/except`)
- Entrada e formatação de dados no terminal (`input`, f-strings, `ljust`)

## Curso

Este projeto faz parte do curso [Python: crie sua primeira aplicação](https://cursos.alura.com.br/course/python-crie-sua-primeira-aplicacao), da [Alura](https://www.alura.com.br/).
