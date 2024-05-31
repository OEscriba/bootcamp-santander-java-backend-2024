# Operadores
Assim como em todas as linguagens de programação, o Java também possui operadores para realizar diversos tipos de operação.

## Atribuição
O mais básico é o `=`, que serve para atribuir valores, como nos exemplos abaixo:  
`String nome = "FERNANDO"; `   
`int idade = 22;`  
`double peso = 68.5;`

## Operadores aritméticos

Os operadores aritméticos são os seguintes:
`double soma = 10.5 + 15.7;`  
`int subtração = 113 - 25;`  
`int multiplicacao = 20 * 7;`  
`int divisao = 15 / 3;`  
`int modulo = 18 % 3;`  
`double resultado = (10 * 7) + (20/4);` (os parentesis indicam a ordem de resolução também)

# Concatenação

É importante ressaltar que, caso esteja lidando com variáveis de texto (como String), o operador `+` irá concatenar ao invés de somar.

Por exemplo, pedindo para exibir o valor da variável abaixo, o resultado seria 31:
`concatenacao = 1+1+1+"1";`

Já desta aqui, seria 1111:
`concatenacao = 1+"1"+1+1;`