# Bordas CSS

> podemos colocar borda em todos elementos

- border é um estilo auto-explicativo que na hora da codificação, solicita 3 parâmetros, que são eles, o tamanho da borda, o estilo da borda e a cor, exemplo.
- ela irá envolver todos os 4 lados do elemento.
- obs: não é colocar os conteúdos dos elementos em si com a borda, mas sim a caixa em que o conteúdo reside.

```css
h1 {
    /*  tamanho | tipo da borda | cor */
    border: 5px solid blue;
}
```

### Definindo borda apenas em um lado
```css
h1 {
    /* borda apenas na parte inferior */
    border-bottom: 1px solid black;
}
  
```

### Arredondando a borda
```css
h1 {
    border-radius: 50px;
    border: 1px solid black;
}