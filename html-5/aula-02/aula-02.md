![Aula 02](/aula-02/img/aula-02.png)

## Aula 02 - Exemplos Básicos de HTML
___

**O que verá nesse post:**
- Documentos HTML
- Declaração <!DOCTYPE>
- Cabeçalhos HTML
- Parágrafos HTML
- Links HTML
- Imagens HTML
- Como Ver Código Fonte HTML
___

### Documentos HTML
- Todos os documentos HTML devem começar com uma declaração de tipo de documento: ``<!DOCTYPE html>.``

- O documento HTML em si começa com ``<html>`` e termina com ``</html>``.

- A parte visível do documento HTML é entre ``<body``> e ``</body>``.

Exemplo
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
</body>
</html>
```
___

### Declaração <!DOCTYPE>
- A declaração ``<!DOCTYPE>`` representa o tipo de documento e ajuda os navegadores a exibir páginas da Web corretamente.

- Ela deve aparecer apenas uma vez, na parte superior da página (antes de qualquer tag HTML).

- ``<!DOCTYPE> ``não é case sensitive.

- Declaração ``<!DOCTYPE>`` no HTML5 é:

``` html
<!DOCTYPE html>
```
___

### Cabeçalhos HTML
Os cabeçalhos HTML são definidos com o ``<h1>`` e vão até `` <h6>``.

``<h1>`` define o título mais importante. ``<h6>`` define o o título menos importante: 

Exemplo
``` html 
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
``` 
___

### Parágrafos HTML
Parágrafos HTML são definidos com a tag ``<p>`` :
```html 
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
___

### Links HTML
Os links HTML são definidos com a tag ``<a>``:
```html 
<a href="https://www.google.com">This is a link</a>
```

- O destino do link é especificado pelo atributo ``href``. 

- Os atributos são usados para fornecer informações adicionais sobre elementos HTML.
___

### Creditos

Esse conteúdo foi retirado e traduzido da documentação oficial do HTML 5.