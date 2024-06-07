# Estruturas Excepcionais (ou Estruturas de Exceção)

Em Java, exceções são similares com erros, mas têm suas diferenças. Explicando de forma simples, um erro é algo que, ao ocorrer, seria inevitável que a aplicação parasse; ao passo que uma exceção é apenas algum fluxo inesperado (por exemplo: dividir um número por zero).

## Try/Catch

Para contornar exceções, nós utilizamos os blocos `try{}catch{}`. Dentro do `try` ficará o bloco de código que deve ser executado, enquanto no `catch` ficará a "resposta" para determinadas exceções, caso elas ocorram.

## Checked and Unchecked Exceptions

Outro conceito importante é o de checked e unchecked exceptions. Basicamente, checked exceptions já são percebidas na fase de compilação do código, e terão que ser necessariamente tratadas (utilizando o `try/catch` ou `throws`).

Já as unchecked exceptions ocorrem durante a execução do programa (runtime). O fato de uma exceção ser unchecked não significa que ela é menos importante, ou que não precisará ser tratada, mas sim que o momento da exceção é diferente.

## Exceções customizadas

Também é possível criar suas próprias exceções, customizando seu sistema para lidar melhor com os fluxos específicos da regra de negócio da ocasião.