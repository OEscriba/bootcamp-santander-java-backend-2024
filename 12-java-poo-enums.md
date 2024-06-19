# Enums

Um enum é um tipo especial de classe, que tem como função disponibilizar para a aplicação objetos imutáveis previamente criados. Um bom exemplo seria um enum com os estados brasileiros, visto que é muito improvável que haja uma alteração nela.

É importante ressaltar que um Enum não é uma lista de constantes, mas sim uma lista de objetos pré-definidos, uma vez que cada item dentro de um Enum terá atributos, métodos, etc.

Abaixo há um exemplo de Enum:
```
// Criando o enum EstadoBrasileiro para ser usado em toda a aplicação.
public enum EstadoBrasileiro {
	SAO_PAULO ("SP","São Paulo"),
	RIO_JANEIRO ("RJ", "Rio de Janeiro"),
	PIAUI ("PI", "Piauí"),
	MARANHAO ("MA","Maranhão") ;
	
	private String nome;
	private String sigla;
	
	private EstadoBrasileiro(String sigla, String nome) {
		this.sigla = sigla;
		this.nome = nome;
	}
	public String getSigla() {
		return sigla;
	}
	public String getNome() {
		return nome;
	}
	public String getNomeMaiusculo() {
		return nome.toUpperCase();
	}
	
}

```

## Boas práticas

Também existem convenções para criar enums. Cada objeto de um enum deve ser escrito em Caps Lock e separado por um underline _

Os valores de cada atributo devem ser definidos logo após cada opção, de forma similar a um ``new``.

Após listar todos os objetos do enum, é necessário encerrar com um ponto e vírgula.

O construtor do enum deve ser privado, uma vez que o propósito de um enum é justamente ser imutável. Da mesma forma, normalmente, o enum terá apenas getters.



