# HTML

> HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. - Wikipedia

Os sites são feitos, em parte, por HTML, você pode entrar em qualquer site no seu navegador, clicar com o botão direito e depois em algo como `ver código fonte` para ver o HTML desse site.


Esse é um exemplo de código html:

```
<html>
  <head>
    <title>Curso HTML</title>
  </head>
  <body>
    <h1>Hello World</h1>
    <p>Esse é um parágrafo</p>
    <img src="/images/example.png" alt="Exemplo">
  </body>
</html>
```

Como você pode ver esse código é formado por <b>tags</b>, que são essas `<nome-da-tag>` e que algumas delas fecham como `</nome-da-tag>` e outras não como é o caso da tag `<img>`.

Você pode perceber também que algumas tags tem <b>atributos</b>, que são informações que você pode colocar dentro da tag `<nome-da-tag atributo="valor do atributo">`, no exemplo acima vemos a tag `<img>` com dois atributos que são o `src` e `alt`.

Você pode testar códigos HTML fazendo um arquivo com a extensão `.html` usando o block de notas e abrindo ele com seu navegador. Por exemplo você poderia copiar o código acima, salvar como `curso.html` e abrir ele com o Google Chrome.

Legal, você já sabe o que são tags, agora vamos ver o que significa cada uma delas.

### html

`<html>` É a tag que diz que este é um documento html, ela é obrigatória para toda página html.

### head

`<head>` É o cabeçalho da sua página, dentro dela você declarar valores e outras tags que vão ser usadas pelo navegador, mas não necessariamente vão aparecer no site.

### title

`<title>` É a tag que define o título da página para o navegador. Sabe o título que aparece na aba ou na janela? Essa tag que define ele.

### body

`<body>` É o corpo da sua página, tudo que estiver dentro dessa tag vai aparecer no site.

### h1

`<h1>` É uma tag de título, existem outras parecidas que são: `<h2>`, `<h3>`, `<h4>`, `<h5>` e `<h6>`. Tente usá-las e ver a diferença.

### p

`<p>` É uma tag para definir parágrafos.

### img

`<img>` É uma tag para colocar imagens na página, os atributos `src` (source/local do arquivo) e alt (texto alternativo caso a imagem não abra) são obrigatórios.

--

Vou adicionar mais conteúdo aqui, mas se você quiser se adiantar, existem muitos cursos e tutoriais na internet sobre esse assunto, por exemplo:

- [XTI](https://www.youtube.com/watch?v=nIduUA04HFo).
- [iMasters](https://imasters.com.br/secao/front-end/html/)

Obrigado.
