# Fontes externas
- fontes externas são utilizadas para serem carregadas juntas ao site em caso que o usuário não tenha a fonte instalada por padrão no computador. 
- para importar fontes externas é bastante utilizado o site "google fonts", aonde conseguimos pegar diversas fontes com diversos "pesos (weight)".
> https://fonts.google.com/
- após selecionar a fonte, temos que incorporar o código gerado pelo site em nosso código html, mais especificadamente no head. Colocamos no HEAD para que ela seja carregada antes de qualquer coisa visual ser gerada para o usuário.
> caso for selecionada mais de uma fonte, com mais de um peso, é sempre válido olhar o "load time", é recomendável e de boa prática deixar sempre em "fast", o que diz respeito ao tempo de carregamento da fonte no site.
```html
Incorpore o código no <head> do seu html

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Chilanka&family=Luckiest+Guy&display=swap" rel="stylesheet">
```
- Após importar em nosso site, temos que realizar a configuração do font-family no CSS.
```css
Chilanka: classe CSS

.chilanka-regular {
  font-family: "Chilanka", cursive;
  font-weight: 400;
  font-style: normal;
}
```

** Com isso, mesmo que o usuário não tenha a fonte do site no computador, não tem problema, o site irá baixar utilizar. 
Obs: Ele não instala a fonte no computador, ele apenas baixa para utilizar na página e logo após fechar o nmavegador é descartado.