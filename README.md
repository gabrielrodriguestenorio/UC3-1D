# Caderno virtual - Lógica da Programação e Algoritmos
### Gabriel Rodrigues Tenório

Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.
__________________________________________________________________________________
### Conteúdo 1 - Variáveis 
O primeiro conteúdo que aprendemos foram as variáveis. Aprendemos suas definiçições e as melhores situações para usar cada uma delas.
```js
var = "variávelVar"
let = "variávelLet"
const = "variávelConst"
```
##### ↑ *As variáveis que aprendemos*
VAR - A variável *var* geralmente tem escopo global, podendo ser modificada e atualizada em qualquer parte do código. Mas ela pode também assumir o escopo de bloco, caso seja declarada dentro de um.

LET - A variável *let* naturalmente tem um escopo de bloco, mas pode ser modificada de algumas maneiras.

CONST - A constante *const* difere-se das outras variáveis por ser imutável, ou seja, sendo impossível modificar o seu valor inicial. O *const* também possui o escopo de bloco.
__________________________________________________________________________________
### Conteúdo 2 - Operadores de Comparação, Lógicos e Matemáticos
O segundo conteúdo que aprendemos foram os operadores (no geral). Aprendemos as diferenças de cada um e suas respectivas aplicações.
##### Os primeiros que aprendemos foram os de Comparação.
```js
1 == "1"           // igual valor - "=="
1 === 1            // igual valor e tipo de dado - "==="
1 > 0              // maior que - ">"
1 < 2              // menor que - "<"
(1 >= 1) (1 >= 2)  // maior ou igual a - ">="
(1 <= 1) (1 <= 0)  // menor ou igual a - "<="
1 != 2             // diferente valor - "!="
1 !== "2"          // diferente valor e tipo de dado - "!=="
```
##### Em seguida, os Matemáticos.
```js
2 + 4 == 6         // adicionar ao valor - "+"
2 - 4 == 2         // subtrair do valor - "-"
2*4 == 8           // multiplicar o valor - "*"
2/4 == 2           // dividir o valor - "/"
```
##### E por último, mas não menos importante, os lógicos.
```js
1 + 2 == 3 && 2 + 4 == 6   // primeira condição E segunda condição "&&"
1 + 2 == 3 || 2 + 4 == 6   // primeira condição OU segunda condição "||"
```
__________________________________________________________________________________
### Conteúdo 3 - If/Else
Outro conteúdo vivenciado foi a estrutura condicional If/Else. Aprendemos a usar parâmetros condicionais e/ou comparativos junto com essa estrutura para criar códigos com finalidade restrita/condicional.
```js
const idade = prompt("Qual sua idade?")
if (idade >= 18) {
 console.log("Você é maior de idade")
} else {
 console.log("Você não é maior de idade")
}
```
##### ↑ *Exemplo de código usando a estrutura If/Else*
Apredemos também a usar o *Else if* na estrutura If/Else.
```js
const fruta = prompt("Digite uma fruta.")
if (fruta == "maçã") {
 console.log("A sua fruta é a maçã! 🍎")
} else if (fruta == "banana") {
 console.log("A sua fruta á a banana! 🍌")
} else if (fruta == "laranja") {
 console.log("A sua fruta á a laranja! 🍊")
} else if (fruta == "uva") {
 console.log("A sua fruta á a uva! 🍇")
} else {
 console.log("Não conheço essa fruta ):"
}
```
##### ↑ *Exemplo de código usando a estrutura If/Else e Else if*
__________________________________________________________________________________
### Conteúdo 3 - Arrays

Depois dO If/Else nós aprendemos a usar as **arrays**. Primeiro criamos uma array básica, usando livros como referência. As arrays nada mais são do que "lista de objetos" que contém vários elementos, estes elementos são como valores "embutidos" na array, e são intrínsecos à ela.
```js
const livros = ["Javascript Assertivo", "ECMAScript", "MongoDB", "Death Note",
"Ordem Paranormal RPG: Sobrevivendo ao Horror", "Duna", "Uma breve História da Ciência"]
```
#### ↑ *Array que utilizei na primeira aula*

Aprendemos também certos métodos básicos que podemos utilizar com as arrays, como o ".length", o ".sort()", o ".join()", entre outros.
```js
const produtos = ["Caixa de som", "Rádio", "Televisão", "Monitor", "Teclado", "Mouse"]
const seçãoSalaDeEstar = produtos.slice(0,3)

console.log(seçãoSalaDeEstar)

// Output: [object Array] (3) ["Caixa de som","Rádio","Televisão"]
```
##### ↑ *Exemplo de array utilizando o método ".slice()*
__________________________________________________________________________________

## Atividades desenvolvidas 
__________________________________________________________________________________
### Atvidade 1 - Lanche

Atividade que envolvia criar um éspecie de algoritmo simples interage com o usuário no contexto de um atendimento de fastfood/restaurante.
O principal conhecimento estudado nessa atividade foi a estrutura condicional if/else.
Abaixo está um trecho do código que usa o if/else.

```js
if(combo == "sim") {
  console.log(`Parabéns, ${nome}, você ganhou um brinde!`)
} else {
  console.log('Ok, volte sempre!')
}
```
__________________________________________________________________________________
### Atvidade 2 - Lanche
