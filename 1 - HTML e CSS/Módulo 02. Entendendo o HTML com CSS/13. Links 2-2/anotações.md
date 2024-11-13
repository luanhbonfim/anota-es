# Links (2/2)

- muitos link's utilizados hoje em dia não são textos, e sim imagens.
```html
<a href="https://www.google.com.br/" target="_blank">
    <img src="https://www.google.com.br/google.jpg">
    <p> Ir para o site do google </p>
</a>
```
- Tudo que está entre a tag "a", está clicável, ao clicar será direcionado para o site definido no atributo.

<br><br>

- tag "a" não serve apenas para te mandar para outros sites, também podemos utilizar para "linkar" seções da nossa página. Exemplo, caso clicar em um título, terá um "scroll" até o conteudo, um direcionamento.
```html
<h1 id="Home"> Página de teste </h1>
........
.......
.......
.......
.......
.......
<a href="#Home"> Voltar para o ínicio </a>
```
- ao clicar, será redirecionado para o inicio da página gerando uma sensação de "scroll", será arrastado até o Home. 
- o href fez uma "ancora" com o id "Home"