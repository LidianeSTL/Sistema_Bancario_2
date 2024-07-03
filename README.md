*SISTEMA_BANCARIO_VERSÃO_2*
 
*DESAFIO:*
Precisamos deixar o código mais modularizado, para isso vamos criar funções para as operações existentes: sacar, depositar e vizualizar o extrato. Além disso, para a versão 2 do nosso sistema precisamos criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com o usuário).


*SEPARAÇÃO_ EM_FUNÇÕES:*
Devemos criar funções para todas as operações do sistema. Para exercitar tudo o que aprendemos neste módulo, cada função vai ter uma regra na passagem de argumentos. O retorno e a forma como serão chamadas, pode ser definida por você da forma que achar melhor.

SAQUE: 
A função saque deve receber os argumentos apenas por nome (keyword only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

DEPÓSITO:
A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Dugesão de retorno: saldo e extrato.

EXTRATO:
A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

NOVAS_FUNÇÕES:
Precisamos criar duas novas funções: criar usuário e criar uma conta corrente. Fique à vontade para adicionar mais funções, exemplo: listar contas, inativar conta.

CRIAR_USUÁRIO:
O programa deve armazenar os usuários em uma lista, um usuário é composto por: nome, data de nascimento, cpf e endereço. O endereço é uma string com o formato: logradouro, número, bairro, cidade/sigla e estado. Deve ser armazenado somente os números do cpf (sem pontos e vírgulas) Não podemos cadastrar 2 usuários com o mesmo cpf
Qual é a estrutura de dados que armazena valor?


CRIAR_CONTA_CORRENTE:
O programa deve armazenar contas em uma lista, uma conta é composta por: agência, numero da conta e usuário. o numero da conta é sequencial, iniciando em 1. O numero da agencia é fixo “0001”. O usuário poder mais de uma conta, mas uma conta pertence a somente um usuario.

