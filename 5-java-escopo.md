# Escopo

No contexto do Java, e neste caso em específico, "escopo" pode ser definido como o ambiente no qual uma variável pode ser acessada.

O escopo de uma variável muda conforme o local aonde ela foi declarada.

Por exemplo, ao declarar uma variável diretamente dentro do bloco de código de uma classe, ela será acessível por tudo que estiver dentro desta mesma classe.

Agora, caso você declare uma segunda variável que está dentro do bloco de código de um método, a variável ficará disponível apenas internamente, dentro do método específico.

No exemplo abaixo, as variáveis `ligada`, `canal` e `volume` estão dentro do escopo da classe, enquanto a variável `novoCanal` está dentro do método `mudarCanal`:

```
public class SmartTv {
    boolean ligada = false;
    int canal = 1;
    int volume = 25;

    public void mudarCanal (int novoCanal) {
        canal = novoCanal;
        System.out.println("Mudando canal para: " + canal);
    }
}
```