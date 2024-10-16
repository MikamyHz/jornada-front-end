![Aula 01](/aula-01/img/aula-01.png)

## Aula 01 - Introdução ao HTML 5

### Introdução ao HTML 5

**O que verá nesse post:**
- O que é HTML?
- Um Documento HTML Simples
- O que é um elemento HTML?
- Navegadores Web
- Estrutura da Página HTML
- História HTML
- Crétidos

___

### O que é HTML?
- HTML significa <b>Hyper Text Markup Language</b>
- HTML é a linguagem de marcação padrão para criar páginas Web
- HTML descreve a estrutura de uma página da Web
- HTML consiste em uma série de elementos
- Os elementos HTML informam ao navegador como exibir o conteúdo
- Elementos HTML rotulam partes do conteúdo como "este é um título", "isso é um parágrafo", "este é um link", etc.

___

### Um Documento HTML Simples
```html
<!DOCTYPE html>
<html>
<head>
<title>Título da página</title>
</head>
<body>
    <h1>Meu Primeiro Cabeçalho</h1>
    <p>Meu Primeiro Parágrafo.</p>
    <a>Meu Primeiro Link</a>
</body>
</html>
```
___

### Exemplo Explicado
- ``<!DOCTYPE html>``
Declaração que define que este documento é um documento HTML5.
- ``<html>``
Elemento raiz de um documento HTML.
- ``<head>``
 Contém meta informações sobre a página HTML.
- ``<title>``
Especifica um título para o página HTML (que é mostrada na barra de título do navegador ou na guia da página).
- ``<body>``
Define o corpo do documento, e é um recipiente para todo o conteúdo visível, tais como cabeçalhos, parágrafos, imagens, hiperlinks, tabelas, listas, etc.
- ``<h1>``
Define um cabeçalho grande.
- ``<p>``
Define um parágrafo.
- ``<a>``
Define um hyperlink.

___

### O que é um elemento HTML?
Um elemento HTML é definido por uma tag inicial, algum conteúdo e uma tag final:

``<tagname>``O conteúdo vai aqui``</tagname>``
Um elemento HTML é tudo, desde a tag inicial até a tag final.

``<h1>``Meu Primeiro Cabeçalho``</h1>``
``<p>``Meu Primeiro Parágrafo.``</p>``
``<a>``Meu Primeiro Link.``</a>``

Nota: Alguns elementos HTML não têm conteúdo (como o ``<br>``). Esses elementos são chamados de elementos vazios. Elementos vazios não têm uma tag final.

___

### Navegadores Web
O propósito de um navegador web (Chrome, Edge, Firefox, Safari) é ler documentos HTML e exibi-los corretamente.

Um navegador não exibe as tags HTML, mas as usa para determinar como exibir o documento:

![Exemplo-1](/aula-01/img/exemplo-1.png)

___

### Estrutura da Página HTML
Abaixo está uma visualização de uma estrutura de página HTML:

![Exemplo-2](/aula-01/img/exemplo-2.png)

Nota: O conteúdo dentro da secção ``<body>`` será exibido em um navegador. O conteúdo dentro do elemento ``<title>`` será mostrado na barra de título do navegador ou na guia da página.

### Creditos

Esse conteúdo foi retirado e traduzido da documentação oficial do HTML 5.