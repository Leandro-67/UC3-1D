
# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

Certo

## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

aprendir sobre as variaveis: const, let, var, if, else, Switch, case

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

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
## Explicação
const: Declara variáveis que não podem ser reatribuídas.
Imutabilidade: const impede reatribuição da variável, mas permite alteração do conteúdo de objetos e arrays.
Exemplo: Usando const, você pode definir variáveis como números, strings, arrays e objetos. Embora o valor da variável não possa ser mudado, o conteúdo interno (como elementos de um array ou propriedades de um objeto) pode ser alterado.

### CONSOLE.LOG
O console.log é uma função usada em JavaScript para exibir mensagens no console do navegador ou ambiente de execução, como o Node.js. Ele é frequentemente utilizado para depuração (debugging), permitindo que o desenvolvedor veja o valor de variáveis ou mensagens personalizadas em tempo real durante a execução do código.

````js
console.log(mensagem);

let nome = "João";
console.log(nome); // Saída: João

let idade = 25;
console.log(nome, idade); // Saída: João 25

````
## Explicação
console: é um objeto global que fornece acesso ao console do navegador ou ambiente de execução.
log(): é um método desse objeto que imprime a mensagem ou o valor de uma variável no console.
Aqui, a variável nome será exibida no console, e a saída será a string "João".
O console.log pode ser usado para imprimir diferentes tipos de dados, como strings, números, arrays e objetos.

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
## Explicação
Exibe uma caixa de diálogo pedindo ao usuário para inserir o nome.
"Nome padrão" é o valor inicial que aparece no campo de entrada.
Verificação:

Se o usuário insere um nome e clica em "OK", o valor inserido é armazenado na variável nome.
Se o usuário clica em "Cancelar", nome será null.
alert:

Mostra uma mensagem com o nome do usuário ou informa que a operação foi cancelada.

