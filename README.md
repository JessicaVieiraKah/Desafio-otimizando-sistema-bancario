# Desafio-otimizando-sistema-bancario
Objetivo geral do código: Separar as funções existentes de saque, depósitos e extratos em funções. Criar duas novas funções: cadastras usuário ( cliente ) e cadastrar conta bancária.
Devemos deixar o código mais modularizado,para isso precisamos criar funções para as operações existentes: sacar, depositar e extrato. Para essa nova versão precisamos criar duas funçoes novas que seriam criar usuário (cliente do banco) e criar conta corrente e vincular ao usuário.
A função saque deve receber os argumentos apenas por nomes(keyword only);
A função deposito deve receber os argumentos apenas por posição (position only;
A função extrato deve receber os argumentos por posição e nome (position only e keyword only);
Para criar o usuário(cliente o sistema deve armazenar os usuários em uma lista, o usuário é composto por: nome, data de nascimento, cpf e endereço;
O endereço é uma string com formato: logradouro - numero - bairro - cidade/sigla do estado;
Deve ser armazenado apenas os numeros do cpf nada de pontos e traços;
Não pode cadastrar duas vezes o mesmo cpf;
Um usuário pode ter várias contas, mas uma conta pertence somente a um usuário.
