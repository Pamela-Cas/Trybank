# Trybank

Boas-vindas ao meu primeiro projeto em C# na eletiva da Trybe.

## Sobre o Projeto

Nesse projeto foi criado uma aplicação para controlar contas bancárias bem como realizar as suas operações básicas de checar um saldo, depositar, sacar e transferir dinheiro. Além disso permiti cadastrar novas contas, faça login e logout no sistema.

## Funcionalidades Implementadas
<details>
  <summary><strong>Projeto Trybank</strong></summary><br />

#### Cadastro de Novas Contas
O sistema permite o registro de novas contas, verificando a existência prévia da combinação de número e agência para evitar duplicatas.

#### Login e Logout
Os usuários podem fazer login e logout, sendo controlado o estado de usuário logado e validada a combinação de número, agência e senha.

#### Verificação de Saldo
Possibilidade de consultar o saldo da conta do usuário logado.

#### Depósito de Dinheiro
Funcionalidade para depositar valores na conta do usuário logado.

#### Saque de Dinheiro
Permite a retirada de valores da conta do usuário logado.

#### Transferência entre Contas
Capacidade de transferir dinheiro entre contas, validando o saldo e a existência das contas envolvidas.

## Habilidades Aplicadas

Durante a realização deste projeto, algumas habilidades foram exercitadas:

- Manipulação de arrays multidimensionais para armazenamento temporário de dados.
- Implementação de funções com validações e tratamento de exceções para garantir a integridade das operações financeiras.
- Separação de responsabilidades e construção de funcionalidades em ordem para facilitar a evolução do sistema.

## Orientação para experimentar o projeto em sua máquina local
<details>
  <summary><strong>Instalação e Execução</strong></summary><br />

1. Clone o repositório:
```sh
git clone git@github.com:Pamela-Cas/Trybank.git
```
2. Entre na pasta do repositório:
```sh
cd trybank 
```
2. Instale as dependências:
Entre na pasta:
```sh
cd src/ 
```
Execute o comando:
```sh
dotnet restore 
```
Sinta-se à vontade para explorar este projeto, acompanhar meu crescimento e contribuir, se desejar. Se você tiver alguma sugestão, feedback ou quiser trocar conhecimentos, será um prazer conectar com você no LinkedIn!
