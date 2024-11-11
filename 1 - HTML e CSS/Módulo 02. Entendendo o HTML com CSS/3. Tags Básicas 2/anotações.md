# Tag's Básicas (2/2)

## Imagem
- Tag destinada a inserção de imagens (internas / externas), por link ou por diretório.
- Temos um atributo chamado "alt", é recomendável por mesmo que seja em branco por questões de SEO. Esse atributo é utilizado para ocasiões que a imagem não carrega corretamente aparecer uma mensagem "descritiva" sobre o que era a imagem. Ou para pessoas que têm deficiência visual, a acessibilidade narrar/descrever a imagem.
```html
<!-- Localmente -->
<img src="./imagem.jpg" alt="Imagem"/>

<!-- Por link (externo) -->
<img src="https://www.google.com.br/google.png" alt="Logo do Google Chrome"/>
```

## Botão
- Tag autoexplicativa.
- Não quebra a linha
```html
<button>Clique aqui</button>
```

## Tag para quebrar linhas
- Podemos colocar vários "br" em uma única linha, se colocarmos 5 br, irá ter 5 "quebra de linhas" ou irá pular 5x
```html
<br />
```

## Tag de listagem

- Por padrão toda lista possui elementos "<strong>li</strong>"

### Lista "NÃO ORDENADA"
- Lista definidas por um pontinho, não são ordenadas.
```html
<ul>
    <li> Farinha </li>
    <li> Ovo </li>
    <li> Sal </li>
    <li> Corante </li>
</ul>
```

### Lista "ORDENADA"
- Lista definidas por um objetos ordenados, exemplo, númerais.
```html
<ol>
    <li> Farinha </li>
    <li> Ovo </li>
    <li> Sal </li>
    <li> Corante </li>
</ol>
```