# Visibilidade dos Recursos

Em Java, temos 4 possíveis modificadores de visibilidade: **public**, **default**, **private** e **protected**.

Estes modificadores determinarão o acesso aos métodos da aplicação.

## Public

O modificador public determina que o método será acessível por toda a aplicação, independentemente do pacote ou classe.

## Default

O modificador default determina que o método será acessível apenas naquele pacote específico. Por exemplo, se um método usando default estiver dentro do pacote `edu.oescriba.poo.exemplo`, ele não poderá ser acessado em `edu.oescriba.poo.outropacote`.

Para utilizar o default, basta não declarar um modificador. Exemplo: `void formatarCEP() {}`

## Private

O modificador private determina que aquele método é acessível apenas pela própria classe.

## Protected

O modificador protected será abordado no futuro.