# Introdução básica sobre javascript

Javascript é uma linguagem interpretada que é rodada no lado do cliente. É usada para fazer animações, validações de dados e diversas outras coisas. Se a gente entender o html como o esqueleto do site, o css como a aparência, o js seria o que daria vida a esse corpo. Dessa forma, vamos ver ao longo desse tutorial básico e bem direto como usar o essencial do js.
	
Para associarmos um código javascript a uma página web, podemos utilizar uma tag chamada `<script></script>`. A partir dessa tag, podemos chamar o js de duas formas: A primeira é simplesmente declarar a tag script e dentro dela escrever o nosso código javascript. A outra forma é criar um arquivo js externo, que vai conter o seu código, e dentro do html declarar a tag script. Essa tag script terá um atributo src, que vai ter como valor o path (caminho) do arquivo js. Lembrando que esse path vai ser dinâmico, ou seja: vai partir do diretório onde o seu arquivo (o html) está. Com isso, não é necessário colocar o js dentro da tag script e consequentemente dentro do html; essa vai ser a forma que iremos utlizar.
	
Exemplos:

```
    //Sem o atributo src

<script>
    //código javascript...
</script>

    //Com o atributo src

<script src="script.js"></script>
```

Tendo visto como a gente faz para incluir o javascript, vamos agora de fato incluí-lo. Então, vamos fazer a coisa mais díficil e hardcore que existe no mundo da programação: Hello World!

Para printar uma mensagem com js, utilizamos algo chamado `console.log()`. Logo, qualquer mensagem que a gente queira printar no console do navegador, terá que ser passada entre esses parênteses da função, dentro de um par de aspas simples ou duplas.

Exemplo:

```
<script>
    console.log('Hello World')
</script>
```

Dessa forma, toda vez que acessarmos o arquivo html respectivo, o js vai ser executado e a mensagem que passamos como parâmetro da função será exibida. Mas onde essa mensagem está? Ela está no console do navegador. Para acessá-lo, você pode clicar com o botão direito do mouse na página, ir em inspecionar e no menu superior, vai ter uma opção de console. Indo lá, teremos acesso ao console da nossa página, muito utilizado para debugação, e a nossa mensagem.