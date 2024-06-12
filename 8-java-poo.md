# Programação Orientada a Objetos (POO)

A POO é um paradigma diferente de programação. Considerando a programação mais "tradicional", temos paradigmas como a "programação estruturada" que tem como foco a clareza e o tempo de desenvolvimento da aplicação, e utiliza fortemente estruturas de bloco, e estruturas de controle e repetição.

Já a POO é um paradigma de maior abstração, que visa traduzir o mundo real para a aplicação através do conceito de "objeto". Ou seja, tudo que existe fisicamente é transformado em um objeto dentro do programa, através das características que serão mencionadas adiante.

## Classes, identidade, atributos e comportamentos

Neste contexto, as **classes** irão, no geral, representar objetos. Ao criar uma aplicação seuindo a POO, primeiro iremos criar os moldes dos objetos, e depois os objetos em si.

Por exemplo: primeiro, criaremos uma classe representando o Estudante (molde do objeto), e depois, os objetos específicos (um Estudante chamado João).

Esta classe terá uma **identidade** e seus **atributos**. A identidade é algo que diferenciará aquele objeto de todos os outros, independentemente dos atributos. Por exemplo, podem haver dois estudantes chamados João, e que tenham a mesma idade, mas na POO eles terão identidades diferentes, que irão distinguí-los.

Já os atributos (ou estados) são as características do objeto em si (nome, idade, sexo, etc).

Além disso, um objeto também possui **comportamentos** (métodos), que representam suas ações (seguindo o exemplo anterior: estudar, correr, brincar, comer, etc).

Concluindo, também temos a ideia de **instância**. Basicamente, toda vez que um novo objeto é criado, falamos que uma nova instância daquela classe (que molda o objeto) está sendo criada.

## Exemplo em Java

```
// Criando a classe Student  
// Com todas as características e compartamentos aplicados

public class Student {
    String name;
    int age;
    Color color;
    Sex sex;

    void eating(Lunch lunch){
      //NOSSO CÓDIGO AQUI
    }
    void drinking(Juice juice){
      //NOSSO CÓDIGO AQUI
    }
    void running(){
      //NOSSO CÓDIGO AQUI
    }
}
```

```
// Criando objetos a partir da classe Student

public class School {
    public static void main(String[] args) throws Exception {
      Student student1 = new Student();
      student1.name= "John";
      student1.age= 12;
      student1.color= Color.FAIR;
      student1.sex= Sex.MALE;

      Student student2 = new Student();
      student2.name= "Sophia";
      student2.age= 10;
      student2.color= Color.FAIR;
      student2.sex= Sex.FEMALE;

      Student student3 = new Student();
      student3.name= "Lily";
      student3.age= 11;
      student3.color= Color.DARK;
      student3.sex= Sex.FEMALE;
    }
}
```

## Organizando classes

Por convenção, as classes costumam ser oganizadas em:
- **Classes de modelo**: São as classes dos atores/participantes da aplicação (exemplo: Empresa, Cliente, NotaFiscal, etc);
- **Classes de serviço**: São as classes que contém a lógica de negócio da aplicação (exemplo: VeiculoService, ClienteService, etc);
- **Classes de repositório**: São as classes de integração com o banco de dados;
- **Classes de utilidade**: São as classes que contém ferramentas utilizadas por toda a aplicação (exemplo: FormatadorCepUtil, FormatadorCpfUtil, etc).