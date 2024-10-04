
# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

Certo

## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

aprendi sobre as seguintes variaveis: const, let, var, if, else, Switch case

Aqui está monstrando as somas, subtração, multiplicação e divisão dos numeros

 ### CONST
  O const em JavaScript é uma palavra-chave usada para declarar variáveis cujo valor não deve ser reatribuído após a inicialização. Isso significa que uma variável declarada com const não pode ser reatribuída, embora o conteúdo interno do valor possa ser modificado se for um objeto ou array.

 
````js

const numero = 10;                // Declara uma constante com valor numérico
const saudacao = "Olá, mundo!";  // Declara uma constante com uma string
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

````

### CONSOLE.LOG
O console.log é uma função usada em JavaScript para exibir mensagens no console do navegador ou ambiente de execução, como o Node.js. Ele é frequentemente utilizado para depuração (debugging), permitindo que o desenvolvedor veja o valor de variáveis ou mensagens personalizadas em tempo real durante a execução do código.

````js
console.log(mensagem);

let nome = "João";
console.log(nome); // Saída: João

let idade = 25;
console.log(nome, idade); // Saída: João 25

````


### PROMPT
Como Funciona o prompt
Exibição da Caixa de Diálogo: Quando prompt é chamado, ele exibe uma caixa de diálogo modal com um campo de entrada e uma mensagem opcional. O usuário pode digitar um valor ou cancelar a ação.

````js

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

prompt("Qual é o seu nome?", "Nome padrão"):

````


### SWITCH CASE
O switch em JavaScript é usado para executar diferentes blocos de código com base no valor de uma variável ou expressão. Ele funciona de maneira semelhante ao if-else, mas é mais adequado quando você tem múltiplas condições a serem verificadas.

````js

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
````


### STRING
Em JavaScript, strings são um tipo de dado primitivo usado para representar texto. Strings são sequências de caracteres que podem incluir letras, números, espaços e símbolos. Elas são fundamentais para manipulação e apresentação de dados textuais em um programa.
Strings podem ser criadas usando aspas simples ('), aspas duplas (") ou crase (`) para template literals.

````js

 let string1 = 'Olá, mundo!';
let string2 = "Bem-vindo ao JavaScript!";
let string3 = `Você tem ${25} anos.`;
````

### VARIAVEIS 
Em JavaScript, variáveis são usadas para armazenar dados que podem ser manipulados e referenciados em diferentes partes do código. Elas atuam como "recipientes" para valores e permitem que esses valores sejam usados e alterados conforme necessário.

## VAR

````js
var x = 10;
console.log(x); // Saída: 10
````

## LET

````js
let y = 20;
console.log(y); // Saída: 20
````

## CONST

````js
const z = 30;
console.log(z); // Saída: 30
````

### IF ELSE
Em JavaScript, if e else são estruturas de controle de fluxo usadas para executar blocos de código com base em condições. Elas permitem que o programa tome decisões e execute diferentes seções de código dependendo se uma condição é verdadeira ou falsa.

````js
if (condição) {
  // Código a ser executado se a condição for verdadeira
} else {
  // Código a ser executado se a condição for falsa
}
````
### NUMBER
Em JavaScript, Number é um tipo de dado primitivo usado para representar valores numéricos. O tipo Number pode armazenar tanto números inteiros quanto números de ponto flutuante (decimais). A seguir, estão algumas das principais características e operações associadas ao tipo Number em JavaScript.

````js
let inteiro = 42;
let decimal = 3.14;
````

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

 
 
