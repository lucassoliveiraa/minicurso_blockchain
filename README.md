# Minucurso BlockChain 

## Introdução

No blockchain existem uma chave publíca que é criada pelo usuário, com ela, é gerado uma chave prívada utilizando alguma função Hash. Desta forma, uma carteira (Wallet) é uma conta com uma chave pública e uma privada, e quando é realizado uma transição a chave pública do usuário que realizou enviou essa mensagem é inserido nesse bloco de transação.

![introdução](introduction.jpeg)

Esse bloco de transação se fecha em algum período de tempo determinado pela blockchain, se tornando imutável e outro bloco é iniciado contendo o endereço para o bloco anterior como uma LinkedList (Isso é o BlockChain).

![Mudança de Estados](statesChange.jpeg)

**Consenso:** máquinas precisam ter consenso sobre operações na rede, por exemplo:
Uma máquina A realiza uma transação para uma máquina B e C ao mesmo tempo, com isso, pode ocorrer que ele esteja realizando essas transações com o mesmo saldo. Ou alguma outra informação ainda não esteja presente em alguma máquina no momento em que é requisitado essa informação e, mesmo assim o usuário acaba sendo direcionado para esse servidor, ou por fim, algumas máquinas malignas tentando validar alguma informação. Portanto, é necessário uma forma para que haja consenso de transições e informaçãoes no banco.

![conflito e consenso](conflict.png)