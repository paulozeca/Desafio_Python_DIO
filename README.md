# Desafio_Python_DIO
Desafios de projetos do bootcamp Coding The Future Vivo - Python AI Backend Developer

## Objetivos do Projeto
Fomos contratados por um grande banco para desenvolver o seu novo sistema. Esse banco deseja modernizar suas operações e para isso escolheu a linguagem Python.
Para a primeira versão do sistema devemos implementar apenas 3 operações: depósito, saque e extrato.

## Regras de negócio

Operação de Depósito:
Deve ser possível depositar valores positivos para a minha conta bancária. A versão 01 do projeto trabalha apenas com 1 usuário,
dessa forma não precisamos nos preocupar em identificar qual é o número da agência e conta bancária. Todos os depósitos
devem ser armazenados em uma variável e exibidos na operação de extrato.

Operação de Saque:
O sistema deve permitir realizar 3 saques diários com limite máximo de R$ 500,00 por saque. Caso o usuário não tenha
saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar o dinheiro por falta de
saldo. Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato.

Operação de Extrato:
Essa operação deve listar todos os depósitos e saques realizados na conta. No fim da listagem deve ser exibido o
saldo atual da conta. Se o extrato estiver em branco, exibir a mensagem: Não foram realizadas movimentações.
Os valores devem ser exibidos utilizando o formato R$ xxx.xx, exemplo:
1500.45 = R$ 1500.45

Menu de Operações:
[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair


# Atualização do Projeto incluindo otimizações do código e novas funções.
Nessa nova versão a desafio02.py o sistema deve estar modularizado, para isso será necessário criar funções para as operações existentes(Depositar, Sacar e Extrato),
além da inclusão  de novas funções e suas opções correspondentes no menu do sistema para permitir a Criação de Usuários (cliente do banco), 
Criação de Contas (criar conta corrente vinculada ao usuário) e Listar as Contas criadas, 
dessa forma o menu inicial ficou com as opções de operações listadas abaixo:

Menu de Operações:
[d]     Depositar
[s]     Sacar
[e]     Extrato
[nc]    Nova conta
[lc]    Listar contas
[nu]    Novo usuário
[q]     Sair

## Função Saque
A função saque deve receber os argumentos apenas por nome (keyword only).
Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

## Função Depósito
A função depósito deve receber os argumentos apenas por posição (positional only).
Sugestão de argumentos: saldo, valor e extrato. Sugestão de retorno: saldo e extrato.

## Função Extrato
A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argunento posicional:saldo e argumento nomeado:extrato.

## Função Criar usuário (Cliente)
O programa deve armazenar os usuários em um lista. Cada usuário é composto por: nome, data de nascimento, cpf e endereço, sendo o endereço uma string com o seguinte formato:
logradouro, nro - bairro - cidade/UF.
Deve ser armazenado somente os números do CPF e não é possível cadastrar mais de um usuário com o mesmo CPF.

## Função Criar Conta Corrente
O programa deve armazenar contas em uma lista, que será composta por:
agência, número da conta e usuário, sendo o numero da conta sequencial e iniciando em 1 e o número da agência fixo com a numeração de "0001". Um usuário poderá ter mais de uma conta, mas uma conta pertence somente a um usuário.





Paulo José Zeca 

https://github.com/paulozeca/Desafio_Python_DIO

https://www.linkedin.com/in/paulojosezeca
