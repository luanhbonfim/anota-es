## Tabelas
- antigamente tabelas eram uma estrutura "padrão" de um site, fugindo totalmente do seu contexto.
- hoje, temos outras funcionalidades para estruturar o site, deixando as tabelas focadas apenas no para o que ela é proposto.
<hr>
- para criar uma tabela, primeiro temos que entender seus componentes:
- table: irá agrupar todos esses elementos e indicar que está sendo criado uma tabela
1. tr: table row - define as linhas
2. td: table data - conteúdo de uma célula da tabela, ou as colunas.
3. th: table head - define uma célula cabeçalho

- sempre a primeira linha será exemplo de quantas células/colunas a tabela irá ter.

```html
<table>
    <tr>
        <!-- Se possui 2 cabeçalhos "células de coluna" indica que o resto da tabela só terá 2 td "coluna" -->
        <th> Cabeçalho 1 </th>
        <th> Cabeçalho 2 </th>
    </tr>

    <tr>
        <td> ... </td>
        <td> ... </td>
    </tr>

    <tr>
        <td> ... </td>
        <td> ... </td>
    </tr>
</table>
```

- Para deixar o código mais sêmantico, temos as tags THEAD e TBODY
1. THEAD -> irá agrupar todos os elementos de cabeçalho
2. TBODY -> irá agrupar todos os elementos do corpo, "tr/td"

```html
<table>
    <thead>
        <tr> 
            <th> </th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td> </td>
        </tr>
    </tbody>
</table>
```