## Maneiras de selecionar elementos "tag"
- No CSS, caso quisermos selecionar apenas elementos específicos, podemos utilizar CLASSES ou ID's.
- São definidos como atributo dentro de alguma tag.
- Os nomes podem ser qualquer um, desde que esteja entre as aspas.
- Porque utilizar isso? Por padrão, se estilizarmos diretamente atráves do elemento, exemplo h1, todos h1 do site irá puxar o mesmo estilo e se for necessário deixar cada um com um estilo, podemos utilizar o ID.

### ID
- Ele é único, portanto, se criamos um ID para uma tag, não podemos colocar em outra e caso colocar, não funcionará.
1. Para começar, temos que definir o ID em uma tag no HTML.
```html
<h1 id="titulo"> Página Inicial </h1>
<h1> </h1>
```

2. Selecionando no CSS
- id's são identificados no css atráves de #
```css
#titulo {
    color: green;
}
```
- Assim, apenas o primeiro H1 terá o estilo aplicado.

<hr>

### CLASS
- Class bastante utilizado para estilizar diversos elementos.
- Diferente do ID, ele pode ser usado em mais de 1 elemento, não é único.
- Um bom caso de reuso.

1. Para começar, temos que definir uma CLASS em uma ou mais tag's HTML.
```html
<h1 class="estilo-padrao"> Titulo inicial </h1>
<p class="estilo-padrao"> Parágrafo.......... </p>
<h2> </h2>
```

2. Selecionando no CSS
- class são identificados no css atráves do . "ponto"
```css
.estilo-padrao {
    font-family: 'Arial', sans-serif;
    text-align: center;
}
```
- Todas as tag's que possuírem a class terá o estilo aplicado.

## Utilizando as seleções em conjunto
- Podemos unir as seleções em uma só separados por vírgula, exemplo:
```css
#titulo, 
.estilo-padrao {
    color: blue;
}
```
## Selecionando um elemento mais específico
- Podemos ainda querer selecionar um elemento específico que contenha a class.
```css
.estilo-padrao h1 {
    font-weight: bold;
}
```
- Assim os elementos h1 que contenha a class irá ter o estilo alterado.

<hr>

- Podemos também fazer isso em elementos que contenham outros elementos dentro, exemplo as listas. 
- **dentro do OL procure os LI e altere a cor para RED**
```css
ol li {
    color: red;
}
```