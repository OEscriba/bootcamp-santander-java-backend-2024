# Anatomia de Classes

Ao criar classes em Java, elas sempre devem ser nomeadas usando Pascal Case, e a classe deve possuir o mesmo nome do arquivo. Classes irão conter métodos e outras funcionalidades em Java. Todas classes ficam dentro do diretório "src", dentro do projeto Java.

## Declarando variáveis

Variáveis devem ser escritas em Camel Case, apresentando o tipo da variável, seu nome e um valor, conforme abaixo:  
`String meuNome = "Fernando";`

Outra possibilidade é declarar a variável sem um valor atribuído:  
`int anoAtual;`

Caso uma variável apresente um valor que não deve ser alterado, ela deve ser escrita em Snake Case e letras maiúsculas (exemplo: `double PI = 3.14`).

Variáveis sempre devem ser nomeadas no singular, exceto quando forem arrays. Exemplo:
`String email = "nome@email.com`
`String [] emails = {"nome1@email.com","nome2@email.com"}`

## Declarando métodos

Métodos devem ser declarados como verbos no infinitivo, em Camel Case, conforme abaixo (depois do "public static"):  
`TipoRetorno nomeObjetivoNoInfinitivo Parametros`

Exemplo:  
`public static String juntarNomeSobrenome (String primeiroNome, String sobrenome){}`

Além disso, é recomendado que métodos tenham apenas uma função. Por exemplo, o método abaixo:
`calcularImprimir(){}`

## Pacotes (packages)

Em Java, simplificando, pacotes servem como diretórios/subdiretórios, com a finalidade de organizar as classes criadas no projeto. Conforme um projeto cresce, esta organização torna-se necessária para saber aonde encontrar cada funcionalidade da aplicação.

A convenção de nomeação de pacotes é:
`finalidade.nomedaempresa.nomedoprojeto`

Também é comum abreviar os termos dentro do nome do pacote, por exemplo: `comercial` vira `com`; ou `organizacional` vira `org`.

Por exemplo, uma empresa chamada EscribaTech, que está vendendo um software de contabilidade, poderia ter os seguintes pacotes:
`com.escribatech.contabilsoft.app`
`com.escribatech.contabilsoft.util`
`com.escribatech.contabilsoft.extensions`

No caso do VS Code, para criar os pacotes corretamente, é necessário criar uma pasta para cada "nível" do pacote. Ou seja, ao invés de criar uma pasta chamada "com.escribatech.contabilsoft.app", é necessário criar a pasta "com", depois a pasta "escribatech" dentro da "com", e assim por diante.

## JavaBeans

JavaBeans são convenções de escrita e organização de códigos em Java para que o código possa ser compreendido universalmente, por outros membros de sua equipe e até mesmo por você no futuro.

As principais convenções já foram mencionadas nos tópicos anteriores :D

