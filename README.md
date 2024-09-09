
# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 

Certo

## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

aprendir sobre as variaveis: const, let, var, if, else, Switch, case

## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

Aqui está monstrando as somas, subtração, multiplicação e divisão dos numeros

 ## CONST

 
````js

const nome1 = "Leandro"
const apelido = "Soares"
const fullname = nome1 + " " + apelido
````


## CONSOLE.LOG

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


## PROMPT

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



````
