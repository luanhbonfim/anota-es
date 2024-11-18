# Label
- em uma explicação mais simples, o label é a descrição de um input, ou o título.
- o label normalmente sempre estará "Linkado" ou "amarrado" a um input por meio do atributo "for".
```html
<label for="teste">Nome</label>
```
- esse for é definido para informar ao navegador que esse label pertence à algum input que tiver o id com o mesmo nome de atributo, exemplo.
```html
<label for="teste">Nome</label>
<input type="text" name="user-name" id="teste">
```
- resumidamente, o for conversa diretamente com o id, ou seja, irão ficar amarrados.
- visualmente, isso não muda nada, porém, caso o usuário clicar no "titulo (label)" a caixa input daquele label irá ser selecionada.
- isso é bastante utilizada nesse exemplo:

```html
    <input type="checkbox" id="check">
    <label for="check">Eu declaro que li e aceito os termos de uso.</label>
```
- caso o usuário clicar na descrição, o checkbox irá ser selecionado ou desselecionado.

## Segunda forma de uso
- dessa forma não precisamos referenciar o FOR com ID
```html
<label>
    Nome completo: <br/>
    <input type="text" name="user-name">
</label>
```