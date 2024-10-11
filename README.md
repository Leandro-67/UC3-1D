# Caderno Virtual - Lógica da Programação e Algoritmos

Boas-vindas! Este é o seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atividades dessa unidade curricular. 

---

## Conteúdo Técnico

Escreva aqui os conteúdos aprendidos.

### Variáveis
Aprendi sobre os seguintes tipos de variáveis: `const`, `let`, `var`, `if`, `else`, `switch case`.

---

### const
O const em JavaScript é uma palavra-chave usada para declarar variáveis cujo valor não pode ser reatribuído após a inicialização. Isso significa que uma variável declarada com const não pode ser alterada, mas se o valor for um objeto ou array, seu conteúdo interno pode ser modificado.

```js
const numero = 10;                // Declara uma constante com valor numérico
const saudacao = "Olá, mundo!";    // Declara uma constante com uma string
const frutas = ["maçã", "banana", "laranja"]; // Declara uma constante com um array
const pessoa = { nome: "João", idade: 30 };  // Declara uma constante com um objeto

// Mostrando os valores das constantes
console.log("Número:", numero);
console.log("Saudação:", saudacao);
console.log("Frutas:", frutas);
console.log("Pessoa:", pessoa);

// Modificando o conteúdo do array e objeto (é permitido)
frutas.push("uva"); // Adiciona "uva" ao array
pessoa.idade = 31;  // Atualiza a idade da pessoa

// Mostrando os valores atualizados
console.log("Frutas atualizadas:", frutas);
console.log("Pessoa atualizada:", pessoa);

```

### console.log
O console.log é uma função usada em JavaScript para exibir mensagens no console do navegador ou no ambiente de execução (como Node.js). É útil para depuração e permite visualizar o valor de variáveis ou mensagens personalizadas durante a execução do código.

```js
console.log("Esta é uma mensagem!");

let nome = "João";
console.log(nome); // Saída: João

let idade = 25;
console.log(nome, idade); // Saída: João 25
```

### prompt
A função prompt exibe uma caixa de diálogo para o usuário inserir um valor. O valor inserido pode ser armazenado em uma variável para ser usado posteriormente.

```js
// Exibindo o prompt e armazenando a entrada do usuário
let nome = prompt("Qual é o seu nome?", "Nome padrão");

// Verificando se o usuário clicou em Cancelar
if (nome !== null) {
  // Mostrando uma mensagem de boas-vindas
  alert("Olá, " + nome + "!");
} else {
  // Mensagem se o usuário clicar em Cancelar
  alert("Você cancelou a operação.");
}
```
### switch case
O switch é utilizado para executar diferentes blocos de código com base no valor de uma variável ou expressão. Ele é útil quando há múltiplas condições a serem verificadas, tornando o código mais legível do que várias instruções if-else.

```js
let diaDaSemana = 3;

switch (diaDaSemana) {
  case 1:
    console.log("Hoje é Domingo");
    break;
  case 2:
    console.log("Hoje é Segunda-feira");
    break;
  case 3:
    console.log("Hoje é Terça-feira");
    break;
  case 4:
    console.log("Hoje é Quarta-feira");
    break;
  case 5:
    console.log("Hoje é Quinta-feira");
    break;
  case 6:
    console.log("Hoje é Sexta-feira");
    break;
  case 7:
    console.log("Hoje é Sábado");
    break;
  default:
    console.log("Dia inválido");
}
```
### Strings
As strings em JavaScript são sequências de caracteres usadas para representar texto. Podem ser criadas com aspas simples ('), aspas duplas (") ou crase (`) para template literals.

```js
let string1 = 'Olá, mundo!';
let string2 = "Bem-vindo ao JavaScript!";
let string3 = `Você tem ${25} anos.`;
```
### Variáveis

### var
O var é uma forma de declarar variáveis em JavaScript, sendo funcional desde as versões mais antigas da linguagem. As variáveis declaradas com var têm escopo de função.

```js

var x = 10;
console.log(x); // Saída: 10
```
### let
A palavra-chave let é usada para declarar variáveis com escopo de bloco, o que significa que elas só estão disponíveis dentro do bloco de código em que foram definidas.

```js
let y = 20;
console.log(y); // Saída: 20
```
### const
O const já foi discutido anteriormente, mas é importante lembrar que ele também cria variáveis com escopo de bloco e não permite reatribuição.

```js
const z = 30;
console.log(z); // Saída: 30
```
### if e else
As instruções if e else são usadas para controlar o fluxo do código com base em condições. O bloco if executa um código se a condição for verdadeira, e o bloco else executa outro código se a condição for falsa.

```js
if (condição) {
  // Código a ser executado se a condição for verdadeira
} else {
  // Código a ser executado se a condição for falsa
}
```
### Number
Em JavaScript, o tipo Number representa valores numéricos, incluindo inteiros e decimais. Esse tipo é usado para realizar operações matemáticas.

```js

let inteiro = 42;
let decimal = 3.14;
```

### Arrays
Um array é uma estrutura de dados usada para armazenar múltiplos valores em uma única variável. Os valores podem ser de diferentes tipos e são acessados por índices, começando pelo índice 0.

```js
// Declaração de um array com três elementos
let frutas = ["maçã", "banana", "laranja"];

// Acessando elementos do array
console.log(frutas[0]); // Saída: maçã
console.log(frutas[2]); // Saída: laranja

// Adicionando um elemento ao array
frutas.push("uva");
console.log(frutas); // Saída: ["maçã", "banana", "laranja", "uva"]

// Removendo o último elemento do array
frutas.pop();
console.log(frutas); // Saída: ["maçã", "banana", "laranja"]

// Verificando o comprimento (quantidade de elementos) do array
console.log(frutas.length); // Saída: 3
```

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

*{Item 1 (https://codepen.io/Leandro-Soares-the-looper/pen/gONXozm)}*
*{Item 2 (https://codepen.io/Leandro-Soares-the-looper/pen/WNqdYqw)}*
*{Item 3 (https://codepen.io/Leandro-Soares-the-looper/pen/JjQeowY)}*
*{Item 4 (https://codepen.io/Leandro-Soares-the-looper/pen/OJedBOx)}*
*{Item 5 (https://codepen.io/Leandro-Soares-the-looper/pen/XWLGNrP)}*
*{Item 6 (https://codepen.io/Leandro-Soares-the-looper/pen/VwovOpw)}*
*{Item 7 (https://codepen.io/Leandro-Soares-the-looper/pen/vYoKBpq)}*
*{Item 8 (https://codepen.io/Leandro-Soares-the-looper/pen/OJKRNKy)}*
*{Item 9 (https://codepen.io/Leandro-Soares-the-looper/pen/mdNrQmy)}*
*{Item 10 (https://codepen.io/Leandro-Soares-the-looper/pen/GRVjwmJ)}*

 
 
