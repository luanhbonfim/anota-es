# Margin e Padding

- Por padrão, um elemento HTML (visível) tem 4 características de "tamanho" no CSS que são:
- - conteúdo -> elemento visível na tela
- - padding -> espaçamento interno
- - border -> borda do elemento ou da "caixa"
- - margin -> espaçamento externo
<p><b>Para mais detalhes inspecionar algum elemento</b></p>

> A tag "body" por padrão vem com 8 px de margin, ao criar um site novo é comum resetar a margin para 0.


## Configurando padding/margin
- Em todos os lados
```css
.exemplo {
    padding: 10px;
}
```

- Apenas na direita
```css
.exemplo {
    padding-right: 10px;
}
```

- Em todos os lados com valores diferentes
```css
.exemplo {
    /* top | right | bottom | left */
    margin: 10px 20px 10px 20px;

    /* top - bottom | right - left */
    padding: 10px 20px;
}