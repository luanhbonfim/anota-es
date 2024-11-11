# Oque é o CSS

- Por padrão, algumas TAG's HTML já vem com um CSS pré-definido.
- CSS é a parte visual do site. O CSS é como podemos chamar de estilização. 
- Um site somente com HTML irá ficar "cru", 0 profissionalismo. Agora com o CSS podemos deixar ele totalmente estilizado, com cores, padrões definidos, margens, tamanhos, etc..
- Utilizamos de exemplo, HTML corpo humano, estruturação. CSS a aparência, a roupa, o estilo.


## 3 formas de inserção do CSS no HTML
1. inline
* inserido diretamente dentro de alguma tag em forma de atributo, exemplo:
```html
<h1 style="color:red; font-size:20px;"> Título </h1>
```
2. interno
* inserido entre a tag "head", nela temos que abrir uma tag style para inserir os códigos css, exemplo:
```html
<head>
    <title> Título da Janela </title>
    <meta charset="UTF-8" />


    <!-- tag interna do css -->
     <style>
        /* códigos css vão aqui dentro */
        /* irá estilizar todos elementos h1 */
        h1 {
            color: red;
            font-size: 20px;
        }
    </style>
</head>
```
3. externo
- inserido de maneira externa, por outro arquivo.
- maneira mais utilizada, uma boa prática de programação.
- criamos um arquivo chamado "style.css".
- importamos esse arquivo dentro da tag de configuração do site "head".
```html
<head>
    ......
    <link rel="stylesheet" href="./style.css" />
</head>
```