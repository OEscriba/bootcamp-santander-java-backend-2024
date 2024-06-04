# Documentação

O Java disponibiliza diversas ferramentas para documentar seu projeto de forma eficiente e organizada.

## Tags

Uma funcionalidade extremamente importante são as Tags. Elas permitem identificar e documentar classes. Elas são representadas com `@`

`@author` - Indica o autor do código  
`@version` - Indica a versão do código  
`@since` - Indica a data de disponibilização do código/recurso  
`@param` - Descrição dos parâmetros do método criado
`@return` - Define o tipo de retorno do método  
`@throws` - Explica se o método lança exceções, e quais são

## Comentários

Outra forma de organizar e esclarecer o código é utilizando comentários. Eles são descrições em texto dentro do código, mas que não serão interpretadas pela linguagem. É importante ressaltar que o uso de comentário não exclui o uso das boas práticas e convenções da linguagem.

Existem 3 tipos: one line, multi-line e documentation.

### One line

`//É representado usando as duas barras no começo da linha`

### Multi-line

```
/* Este é um 
* comentário 
* de várias linhas
*/ 
```

### Documentation

```
/** Já este aqui é um comentário
  * com finalidade de documentação.
  * Ele usa dois asteriscos no começo
  */
```