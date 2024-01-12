## Pointers

![](../assets/ponteiros.jpg)

In a restaurant, tables are usually numbered. These numbers allow a waiter to assign everything that was ordered by clients seated at these tables. Then, the client can be charged correctly when leaving the restaurant. Afterwards, the order list must be erased. Otherwise, a new client will pay more than he consumes.

In computer programming, **pointers** are addresses (values, numbers) used to point out areas where values are stored. These areas may be statically or dynamically allocated, i.e., allocated before or during program execution. In static allocation, we reserve a space that will last the whole execution of the program. In the kitchen, for instance, we could reserve a table for the owner of the restaurant. It will be allocated all the time. In dynamic allocation, we do not know how many areas a program will require. We also do not know how many clients a restaurant will serve on a given day. A programmer, or the owner of the restaurant, may choose and combine the types of allocation that best suit your needs.



Em restaurantes, esse rearranjo é comum, por exemplo, quando o espaço de mesas é dividido em salões. Em dias menos movimentados, alguns salões ficam fechados para facilitar o trabalho dos garços, o que pode ser dinamicamente modificado caso a procura aumente num dado momento no dia. Também é comum que grupos desejem rearranjar mesas de forma que todos fiquem juntos. Para isso, basta que as identificações das mesas sejam temporariamente alteradas, ou seja, que as mesas 1, 2 e 3, num dado momento, sejam apenas a mesa 1. Esse rearranjo é muito natural em restaurantes, assim como na alocação de memória de computadores, pois são mecanismos manipulados de forma dinâmica. 

Outro termo em Computação que frequentemente encontramos atrelado a ponteiros é a **coleta automática de lixo**. Imagine que moremos num país corrupto onde, eventualmente, clientes saem do restaurante sem pagar. Isso acarretará vários problemas, além do prejuízo do restaurante: 1) a mesa continuará ocupada até que se descubra que o cliente não se encontra mais no restaurante; 2) novos clientes podem ter que aguardar por uma eventual falsa lotação do restaurante. 

Uma forma moderna de resolver o problema acima seria a adoção de um sistema automático de cobrança. Toda vez que um cliente entra num restaurante, seu cartão de crédito é atrelado a um número de mesa a partir daquele momento. Na porta de saída do restaurante, o cartão do cliente é reconhecido e são lançados os valores correspondentes aos seus pedidos, além da liberação da mesa para novos clientes. Ou seja, essa cobrança acontece de forma automática. Na Computação, esse "comportamento corrupto" é um pouco mais frequente, o que torna essa cobrança automática muito importante para o funcionamento correto do sistema. 

