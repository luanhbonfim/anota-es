# Tag "a" (ancora) - (link)

- atributo 'href' além de direcionar para outros sites (link), pode ser utilizado para referenciar outras páginas html dentro do próprio projeto, exemplo:
```html
<a href="sobre.html">Clique aqui para saber mais</a>
<!-- caso tiver em outro diretório -->
<a href="diretorio/sobre.html">Clique aqui para saber mais</a>
```
- atributo 'target' utilizado para abrir outra janela/aba quando o usuário clicar no link.
- bastante utilizado quando temos link's externos
```html
<a href="sobre.html" target="_blank">Clique aqui para saber mais</a>
```
- atributo "title", utilizado para dar um título para o link
- ao passar o mouse por cima do link irá ser exibido o titulo
```html
<a href="sobre.html" title="Sobre">Clique aqui para saber mais</a>
```