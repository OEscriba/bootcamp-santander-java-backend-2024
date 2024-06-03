# Métodos

Ao criar métodos em Java, é necessário sempre pensar em certos critérios, além das convenções de escrita e nomeação. Seguindo-os, todos os métodos criados serão claros e eficientes, facilitando na compreensão e utilização.

Abaixo, seguem alguns critérios importantes:

## 1 - Proposta principal do método

É importante definir de forma clara qual será a proposta daquele método, ou seja, qual problema ele vai resolver, ou qual tarefa ele irá cumprir.

## 2 - Tipo de retorno esperado

Qual será o tipo do resultado deste método? Por exemplo, se a função do método for somar dois números, podemos esperar que o retorno seja um `double`.

Além disso, nem todo método tem um retorno. Nestes casos, eles são representados com `void`.

## 3 - Parâmetros necessários para execução

Quais parâmetros são necessários para o funcionamento do método? Ainda no exemplo da soma, seriam necessários pelo menos dois números para executar um método `somar(){}`

## 4 - Exceções do método

Caso durante a execução do método possam ocorrer exceções, é necessário que elas já estejam previstas, e tenham uma resposta apropriada. Por exemplo, em um método `dividir(){}`, é necessário que haja uma forma de lidar com uma divisão por 0, que naturalmente resultaria em erro.

## 5 - Visibilidade do método

Nem todos os métodos precisam estar disponíveis para a aplicação como um todo, às vezes é interessante que eles estejam disponíveis apenas dentro de um pacote específico, ou da própria classe. As palavras-chave para isso isso são `public` e `private`.


