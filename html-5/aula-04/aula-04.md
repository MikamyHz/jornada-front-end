![Aula 04](/aula-04/img/aula-04.png)

## Aula 04 - Atributos HTML
___

**O que verá nesse post:**
- Atributos HTML
- O atributo ``src``
- Atributo ``width`` - ``height``
- O atributo ``alt``
- O Atributo ``style``
- O atributo ``lang``
- O atributo ``title``
- Sugerimos: Sempre Use Atributos em Minúsculas
- Sugerimos: Sempre Cite Valores de Atributo
- Aspas Simples ou Duplas?
- Resumo do Capítulo
___

### Atributos HTML
Os atributos HTML fornecem informações adicionais sobre elementos HTML.

- Todos os elementos HTML podem ter atributos
- Os atributos fornecem informações adicionais sobre elementos
- Os atributos são sempre especificados em a tag de início
- Os atributos geralmente vêm em pares nome/valor como: name="value"
___

### O Atributo ``href``

A tag ``<a>``  define um hiperlink. O atributo href especifica o URL da página que o link vai para:

```html
<a href="https://www.google.com">Visit Google</a>

```
___

### O Atributo ``scr``

O tag ``<img>`` é usada para incorporar um imagem em uma página HTML. O atributo ``src`` especifica o caminho para a imagem a ser exibida:

```html
<img src="image.jpg">
```

Existem duas maneiras de especificar o URL no atributo src :

1. URL absoluta Links para uma imagem externa hospedada em outro site. Exemplo: src="https://www.w3schools.com/images/img_girl.jpg".

Notas: Imagens externas podem estar sob direitos autorais. Se você fizer não obter permissão para usá-lo, você pode estar em violação das leis de direitos autorais. Em além disso, você não pode controlar imagens externas; de repente, pode ser removido ou mudou.

2. URL relativa - Links para uma imagem hospedada dentro o site. Aqui, o URL não inclui o nome de domínio. Se o URL começar sem uma barra, ela será relativa à página atual. Exemplo: src="image.jpg". Se o URL começar com uma barra, ele será relativo ao domínio. Exemplo: src="/images/image.jpg".

Dica: É quase sempre melhor usar URLs relativos. Eles não quebrará se você mudar de domínio.

___

### Atributo ``width`` - ``height``

A tag `<img>` também deve conter os atributos `width` e `height`, que especificam a largura e altura da imagem (em pixels):

```html
<img src="image.jpg" width="500" height="600">
```
___ 

### O atributo `alt`
É necessário o atributo `alt` para a tag `<img>` especifica um texto alternativo para uma imagem, se a imagem por algum motivo não puder ser exibida. Isso pode ser devido a uma conexão lenta ou um erro no atributo `src`, ou se o usuário usa uma tela de leitor.

```html
<img src="image.jpg" alt="Image Example">
```
___

### O Atributo `style`

O atributo `style` é usado para adicionar estilos um elemento, como cor, fonte, tamanho e muito mais.

```html
<p style="color:red;">This is a red paragraph.</p>
```
___

### O atributo `lang`
Você deve sempre incluir o atributo `lang` dentro da tag `<html>`, para declarar o idioma da página Web. Isso serve para ajudar os motores de busca e navegadores.

O exemplo a seguir especifica o Português como idioma:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<body>
...
</body>
</html>
```

Os códigos de país também podem ser adicionados ao código de idioma no atributo `lang`. Assim, os dois primeiros caracteres definem a linguagem da página HTML, ou seja, a linguagem e os dois últimos personagens definem o país.

O exemplo a seguir especifica o inglês como idioma e os Estados Unidos como o país:

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```
___ 

### O atributo `title` 

O atributo `title` define um informações extras sobre um elemento.

O valor do atributo title será exibido como uma dica quando passe o mouse sobre o elemento:

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```
___ 

### Sugerimos: Sempre Use Atributos em Minúsculas
O padrão HTML não requer nomes de atributos minúsculos.

O atributo title (e todos os outros atributos) pode ser escrito com maiúsculas ou minúsculas como título ou TÍTULO.

No entanto, W3C recomenda atributos minúsculos em HTML, e atributos minúsculos para tipos de documentos mais rigorosos, como XHTML.

___ 

### Sugerimos: Sempre Cite Valores de Atributo
O padrão HTML não requer citações em torno de valores de atributos.

No entanto, W3C recomenda citações em HTML e citações para tipos de documentos mais rigorosos como XHTML.

Bom:

```html
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
```

Ruim:

```html
<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
```

Às vezes você tem que usar citações. Este exemplo não será exibido o atributo title corretamente, porque contém um espaço:

```html
<p title=About W3Schools>
```

### Aspas Simples ou Duplas?
Aspas duplas em torno de valores de atributos são as mais comuns em HTML, mas aspas únicas também podem ser usadas.

Em algumas situações, quando o próprio valor do atributo contém aspas duplas, é necessário usar aspas simples:

```html
<p title='John "ShotGun" Nelson'>
``` 
Ou vice-versa:
```html
<p title="John 'ShotGun' Nelson">
```
___ 

### Resumo do Capítulo
- Todos os elementos HTML podem ter atributos
- O atributo `href` da tag `<a>` especifica o URL da página para a qual o link vai.

- O atributo `src` da tag `<img>` especifica o caminho para a imagem a ser exibida.

- Os atributos `width` e `height` da tag `<img>` forneça informações de tamanho para imagens.

- O atributo `alt` de `<img>` fornece um texto alternativo para uma imagem.

- O atributo `style` é usado para adicionar estilos para um elemento, como cor, fonte, tamanho e muito mais.

- O atributo `lang` do `<html>` tag declara o idioma da página Web

- O atributo `title` define um extra informações sobre um elemento.

___ 

### Créditos

Esse conteúdo foi retirado e traduzido da documentação oficial do HTML 5.