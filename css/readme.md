# CSS

> Cascading Style Sheets (CSS) é um simples mecanismo para adicionar estilo (cores, fontes, espaçamento etc) a um documento web.
> Em vez de colocar a formatação dentro do documento, o CSS cria um link (ligação) para uma página que contém os estilos. Quando quiser alterar a aparência do portal basta portanto modificar apenas um arquivo.
> Wikipedia

Para adicionar estilo com o CSS em uma página HTML, vou vai precisar da tag `style`. Vamos usar o HTML da página anterior:

```
<html>
  <head>
    <title>Curso HTML</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

Você pode usar a tag `style` de duas maneiras:

- escrevendo os estilos na tag mesmo

```
<html>
  <head>
    <title>Curso CSS</title>
    <style>
      AQUI VÃo OS SEUS ESTILOS
    </style>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

- criando um link (com a tag `link`) para um arquivo com a extensão `.css`

```
<html>
  <head>
    <title>Curso CSS</title>
    <link rel="stylesheet" href="/style.css" />
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

Veja que estilos não fazem parta do corpo da página, então eles não ficam dentro da tag `body`, mas sim dentro da tag `head`.

Existe um post excelente no site da Mozilla ([developer.mozilla.org](https://developer.mozilla.org)) que cobre os assuntos essênciais para qualquer pessoa que quer entrar para o desenvolvimento web.

O post é o [CSS Básico](https://developer.mozilla.org/pt-BR/docs/Aprender/Getting_started_with_the_web/CSS_basico).

Faça bom uso do site da Mozilla porque ele vai responder muitas das suas perguntas.
