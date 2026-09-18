CASSINO DA FORTUNA - C

Esse projeto simula o funcionamento de um jogo de cassino usando a linguagem C, onde o usuário deposita um dinheiro na sua carteira, escolhe um valor para apostar e tenta a sorte.

FUNCIONAMENTO:

Ao executar o programa, o usuário deverá depositar um valor desejado e escolher um valor de aposta, o resultado é calculado com base em 3 números sorteados de 0 a 2, com os resultados possíveis:

Três números diferentes: O usuário perde todo o valor apostado
Dois números iguais: O usuário perde metade do valor apostado
Três números iguais: O usuário ganha o dobro do valor apostado

O programa roda em um loop eterno, e só é encerrado quando o usuário decidir que não quer fazer uma nova aposta depois de ter apostado.

CONSIDERAÇÕES:

O foco nesse programa foi principalmente no tratamento de erros, onde busquei cobrir o máximo de erros possíveis sem que o programa abortasse. Cobri entradas inválidas no teclado e apostas maiores que o valor na carteira, cuidando para que tudo gerasse uma mensagem indicando o que o usuário fez errado e pedindo uma nova entrada.

Além disso, essa foi minha primeira experiência com a função rand da biblioteca <stdlib.h>, que funciona de forma diferente das funções randomizadoras que trabalhei anteriormente, como a função random do Python. A função rand gera um número aleatório tendo uma seed como base; se a seed for sempre a mesma, a função irá gerar sempre o mesmo número. Para contornar isso, usei a biblioteca <time.h> para trazer um número para a seed com base na data e hora atuais, assim a cada instante a seed muda automaticamente.

Esse projeto foi extremamente interessante e divertido de fazer. Embora a linguagem C seja um pouco mais arcaica e complexa, ela oferece funcionamentos únicos com maior liberdade ao programador, provando por que essa linguagem continue sendo tão poderosa mesmo com o passar dos anos.
