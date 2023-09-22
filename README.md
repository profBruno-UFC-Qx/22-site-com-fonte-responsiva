# Descrição

Neste exercício, você irá criar uma página web que exibe uma galeria de imagens que deverá ser estilizado.

O objetivo deste exercício é praticar o uso de seletores CSS pseudo-classes.

**Todas as alterações devem ser feitas nos arquivos já existentes**

* src/index.html -> quando for necessário alterar HTML
* src/css/estilo.css -> quando for necessário alterar CSS
* src/js/script.js -> quando for necessário alterar JavaScript

## Instruções:

1. Altere o arquivo **src/index.html** para que o tamanho da fonte do `body` seja de 16px.
2. Dentro do `<body>`, crie um título da página (`<h1>`), um parágrafo de texto (`<p>`).
3. Faça com que o tamanho da fonte do `h1` seja 4 vezes o tamanho do body.
4. O tamanho da fonte do paragrafo deve ser metade do tamanho da fonte do `h1`.
5. Usando `media queries`, ajuste os estilos de fonte e espaçamento para tornar o site responsivo.
   *  Quando a largura da tela for menor que 600 pixels, modifique os tamanhos de fonte para acomodar dispositivos menores.
   *  O tamanho da fonte do `h1`deve ser 2 vezes o tamanho da fonte do `body`.
   *  Lembre-se, o tamanho da fonte do título deve continar sendo o dobro do tamanho da fonte do parágrafo.    
6. O `padding` de todos os elementos do site deve variar conforme o tamanho da tela:
    * Em telas maiores que 900px, o `padding` deve ser de 24px.
    * Em telas menores que maiores que 600px e menores ou igual a 900px, o `padding` deve ser de 20px.
    * Em telas menores que 600px, o `padding` deve ser de 14px.

Dicas:

* Use a media query @media screen and (`min-width:`) para aplicar os estilos responsivos.
* Utilize a unidade **rem** para dimensionar os tamanhos das fontes

**Importante**

* A ténica que você deve utilizar no exercício não é a mais indicada quando se trata de responsividade de fontes. O exercício tem um caráter puramente didático.


## Recomendações

**Certifique-se de validar seu código HTML usando um validador como o [W3C Markup Validation Service](https://validator.w3.org/), para garantir que seu código esteja sem erros e bem formado**.

**Experimente validar o seu código CSS em sites como:**

- <a href="https://jigsaw.w3.org/css-validator/" target="_blank">W3C CSS validation Service</a>
- <a href="https://beautifytools.com/css-validator.php" hreflang="en" target="_blank">Beatifytools CSS validator</a>
