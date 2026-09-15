# Aula BackEnd

|Tecnologias|Descrição|
|--|--|
|[Miro](https://miro.com/)|Utilizado para o esquema conceitual|
|[Vscode](https://code.visualstudio.com/)|Utilizado para fazer os exemplos de programas|

<br>

|Contribuidores|Perfil|
|--|--|
|Matheus Dorigan Paiato|<a href="https://github.com/matheuszinpaiato-maker">Github|
|Leandro Imenes Oliveira|<a href="https://github.com/LeandroImenes">Github|

<br>

## Esquema de exemplo
<img src="introducao.png">
<img src="variaveis.png">
<img src="sinais.png">
<img src="condicionais.png">
<img src="funcoes.png">

## Atividade
Crie um arquivo no VS Code chamado mercado.js para um mercado que quer calcular o preço final de uma compra com 3 produtos. Se o preço final for maior que 200 reais, então o cartão não passa.

## Entrega
Envie a atividade pelo <a href="https://forms.cloud.microsoft/r/bhtgJ270Ec?origin=lprLink">Formulário

## Correção da atividade:

``` JavaScript
let macarrao = 30
let arroz = 20
let feijao = 10

function calcularTotal(macarrao, arroz, feijao) {
    return macarrao + arroz + feijao
}

function processarCompra(macarrao, arroz, feijao) {
    let total = calcularTotal(macarrao, arroz, feijao)
    return total
}

let total = processarCompra(macarrao, arroz, feijao)

console.log("Preço total da compra foi R$" + total.toFixed(2))

if (total > 200) {
    console.log("A compra falhou. O cartão não passou.")
} else {
    console.log("A compra foi um sucesso. Volte sempre!")
}
```
