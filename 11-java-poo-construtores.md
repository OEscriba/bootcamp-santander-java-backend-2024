# Construtores

A função de um construtor é que, na hora da criação (instanciação) de um novo objeto, já sejam informados atributos essenciais daquele objeto.

No exemplo abaixo, ao criar um novo objeto Pessoa, seriam solicitados o CPF e o Nome:
```
public class Pessoa {
	private String nome;
	private String cpf;
	private String endereco;
	
	// método construtor
	// o nome deverá ser igual ao nome da classe
	public Pessoa (String cpf, String nome) {
		this.cpf = cpf;
		this.nome = nome;
	}
	
	//...
	//getters
	//setters
}
```

A utilização na prática ficaria desta forma abaixo:
```
public class SistemaCadastro {
	public static void main(String[] args) {
		//criamos uma pessoa no sistema
		Pessoa marcos = new Pessoa("06724506716","MARCOS SILVA");
		
		//continua ...
		
	}
}
```