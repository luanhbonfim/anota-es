# Formulários

> Quando se fala em formulário é tudo aquilo que o usuário irá digitar e o site irá receber

- normalmente temos mais de um formulário em um único site, portanto, é necessário "agrupar" para os dados não se perderem em outros formulários. A tag que utilizamos para agrupar é a "form"
- em tags 'form' temos 2 atributos opcionais, que são:
- - action: específica para onde irá as informações
- - method: específica qual método HTTP será utilizado, get ou post.
- - - GET: irá pegar as informações e irá jogar na URL, tornando menos seguro, expondo os dados.
- - - POST: irá manter em "segredo" os dados enviados, serão enviadas internamente, não será exposta na URL. Utilizado em telas de login.