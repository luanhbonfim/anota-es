## Select

- um elemento parecido com os input's que também são bastantes utilizados em formulários.
- ao clicar sobre ele abre uma "Lista" de valores para selecionar, podendo ser único ou de múltipla escolha, basta configurar.
<hr>
<p> -> Para começar, temos que abrir a tag "select" que contem uma tag de fechamento.<br> Entre as tag's, iram conter os "option" que será cada opção para ser selecionado.</p>

<br />

Exemplo:
```html
<!-- 
    os selects também necessitam do atributo "Name" para identificação na hora do envio do form
    outros 2 atributos que o select pode ter são:
    - size: informa quantas opções podem aparecer na tela, irá aumentar a janela do select.
    - multiple: possibilita escolher mais de uma opção
 -->
<select name="select-exemplo">
    <!--
        nos options, temos 3 atributos que são:
        - value: o que será enviado junto ao form para o backend, se não for específicado, será enviado o que está entre as tags "Option".
            exemplo opção 1, será enviado "opt-1", já na opção 2, será enviado "Opção 2"
        - disabled: desabilita a opção para escolha
        - selected: ao iniciar a página é a opção que ficará selecionada por padrão.
    -->
    <option value="opt-1"> Opção 1 </option>
    <option> Opção 2 </option>
    <option value="opt-3"> Opção 3 </option>
    <option value="opt-4" selected disabled> Opção 4 </option>
</select>
```