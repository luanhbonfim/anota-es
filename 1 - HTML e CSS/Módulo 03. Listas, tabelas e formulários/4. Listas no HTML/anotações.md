# Listas 

## Não ordenada
- em listas não ordenadas podemos alterar o tipo do indicador da lista no css, com o atributo, list-style. 
- nele podemos definir se irá ser um círculo, quadrado, círculo preenchido, etc..
```css
ul {
    list-style: square;
}
```
- também podemos ter listas aninhadas
```html
<ul>
    <li> Café </li>
    <li> 
        Chá
        <ul>
            <li> Chá verde </li>
            <li> Chá preto </li> 
        </ul>
    </li>
    <li> Leite </li>
```

## Ordenadas
- podemos alterar o tipo da sequência a ser seguida no html com o atributo type.
- temos diversos tipos de sequências que incluem, romanas, númericas, alfabéticas, etc..
```html
<!-- 
    SEQUÊNCIAS
    I -> número romano em upper case
    i -> número romano em lower case
    A -> alfabético em upper case
    a -> alfabético em lower case[
    1 -> númerico
 -->
<ol type="I">
    <li> Teste 1</li>
    <li> Teste 2 </li>
    <li> Teste 3 </li>
</ol>
```
- também temos o atributo "start", ele define de qual colocação a sequência irá começar.
```html
<ol type="I" start="3">
```
- configuração acima irá começar do terceiro número romano