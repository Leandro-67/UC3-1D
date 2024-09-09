
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

 
````js

const nome1 = "Leandro"
const apelido = "Soares"
const fullname = nome1 + " " + apelido
````


### CONSOLE.LOG

````js

console.log("Meu nome é:" + fullname);

let a = 20
let b = 30 
let soma = a + b

console.log(soma)

let c =24
let d = 65
let subtrair = c - d

console.log(subtrair)

let e = 78
let f = 75
let multiplicar = e * f

console.log(multiplicar)


let g = 56
let h = 54
let dividir = g / h

console.log(dividir)

const pi = 23478

const be = 645
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
## Explicação
Exibe uma caixa de diálogo pedindo ao usuário para inserir o nome.
"Nome padrão" é o valor inicial que aparece no campo de entrada.
Verificação:

Se o usuário insere um nome e clica em "OK", o valor inserido é armazenado na variável nome.
Se o usuário clica em "Cancelar", nome será null.
alert:

Mostra uma mensagem com o nome do usuário ou informa que a operação foi cancelada.

