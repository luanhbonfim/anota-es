# altura e largura

- tomar cuidados ai utilizar px, são valores fixos
- % bastante utilizado para deixar projetos responsivos
- max e min são propriedades obrigátorias, caso tiver, elas irão prevalecer sempre.
- tomar cuidado ao definir tamanho de elementos sem definir box-sizing, pois, sem ele, os elementos deixam de ter o seu tamanho real que foi definido no css e acaba somando com o padding e a borda, ex.
```css
.exemplo {
    height: 400px;
    width: 400px;
    padding: 10px;
    border: 5px solid red;
}
```
- no exemplo acima ficará 430x430, não respeitando o tamanho proposto que deveria ser 400x400
- para resolver isso temos que definir a seguinte propriedade.
```css
* {
    box-sizing: border-box;
}
```
- essa propriedade fara que o padding e a borda seja somado em cima do tamanho proposto, sem "roubar", ou seja, utilizar os 400 definido para o conteúdo, borda e padding.
- por padrão essa propriedade vem com "content-box", significa que o tamanho da caixa tem que ser definido pelo conteúdo
- colocando "border-box", irá informar que o tamanho vai incluir o padding e o border.