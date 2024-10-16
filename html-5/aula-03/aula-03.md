![Aula 03](/aula-03/img/aula-03.png)

## Aula 03 - Elementos HTML
___

**O que verá nesse post:**
- Elementos HTML
- Elementos HTML Aninhados
- Nunca Pule a Tag Final
- Elementos HTML Vazios
- HTML Não é Sensível a Casos
___

### Elementos HTML
O HTML elemento é tudo, desde a tag inicial até a tag final:
``<tagname>``O conteúdo vai aqui``</tagname>``

Exemplos de alguns elementos HTML:

``<h1>``My First Heading``</h1>``
``<p>``My first paragraph.``</p>``

![Aula 03](/aula-03/img/exemplo-1.png)

Nota: Alguns elementos HTML não têm conteúdo (como o ``<br>``). Esses elementos são chamados de elementos vazios. Elementos vazios não têm uma etiqueta final!
___

### Elementos HTML Aninhados
Elementos HTML podem ser aninhados (isso significa que os elementos podem conter outros elementos).

Todos os documentos HTML consistem em elementos HTML aninhados.

O exemplo a seguir contém quatro elementos HTML (``<html>`` ``<body>`` ``<h1>`` e ``<p>``):

Exemplo:
```html 
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

Exemplo Explicado

O ``<html>`` elemento é o elemento raiz e define todo o documento HTML.

Tem uma tag de início ``<html>`` e uma tag final ``</html>``.

Então, dentro do elemento ``<html>``  existe o elemento ``<body>``:

```html 
<body>
<h1>My First Heading</h1>
<p>My first paragraph.</p>
</body>
```

O elemento ``<body>`` define o corpo do documento.

Tem uma tag de início ``<body>`` e uma tag final ``</body>``.

Então, dentro do ``<body>`` temos dois outros elementos: ``<h1>`` e ``<p>``:

```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

O elemento ``<h1>`` define um cabeçalho.

Tem uma tag de início ``<h1>`` e uma tag final ``</h1>``:

```html 
<h1>My First Heading</h1>
```
___

```html
<p>My first paragraph.</p>
```

O elemento ``<p>`` o  define um parágrafo.

Tem uma tag de início ``<p>`` e uma tag final ``</p>``:
```html

```
___

### Nunca Pule a Tag Final
Alguns elementos HTML serão exibidos corretamente, mesmo se você esquecer a tag final:

Exemplo: 

```html 
<html>
<body>
<p>This is a paragraph
<p>This is a paragraph
</body>
</html>
```

No entanto, nunca confie nisso! Resultados inesperados e erros podem ocorrer se você esquecer a tag final!

___

### Elementos HTML Vazios

Elementos HTML sem conteúdo são chamados de elementos vazios.

A tag ``<br>`` define uma quebra de linha, e é um elemento vazio sem uma tag de fechamento:

```html 
<p>This is a <br> paragraph with a line break.</p>
```

HTML Não é Sensível a Casos
Tags HTML não são sensíveis a maiúsculas: <P> significa o mesmo que <p>.

O padrão HTML não requer tags minúsculas, mas W3C recomenda minúsculas em HTML, e demandas minúsculas para tipos de documentos mais rigorosos, como XHTML.

___

### HTML Não é Sensível a Casos
Tags HTML não são sensíveis a maiúsculas: ``<P>`` significa o mesmo que ``<p>``.

O padrão HTML não requer tags minúsculas, mas W3C recomenda minúsculas em HTML, e demandas minúsculas para tipos de documentos mais rigorosos, como XHTML.
___

### Creditos

Esse conteúdo foi retirado e traduzido da documentação oficial do HTML 5.