# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

. Fundamentos do Javascript
. 


## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 

# if else
### A função do if else e permite executar alguns comandos se uma condição for verdadeira e outros se ela for falsa. 
#### Atividade feita no CodePen
 
 ```js
const nome = prompt("Qual e o seu nome?");
const lanche = prompt("Diga seu lanche");

const combo = prompt("deseja comprar nosso combo feliz?");

if (combo == "sim") {
  console.log(`parabéns,${nome},você ganhou um, brinde`);
} else {
  console.log("Muito obrigado(a), volte sempre!");
}
```

# switch case
### A função switch case é uma estrutura de controle de fluxo que permite executar um bloco de código com base na avaliação de uma expressão.
#### Atividade feita no CodePen
 ```js
const remedio = prompt(`Qual remedio o semhor quer comprar`);
const bairro = prompt(`Qual o bairro que o senhor mora`);

switch (remedio) {
  case "Paracetamol":
    console.log(`O produto ${remedio}, custa R$ 11,29.`);
    break;
  case `Ibuprofeno`:
    console.log(`O produto ${remedio}, custa R$ 10,32.`);
  case `Losartana`:
    console.log(`O produto ${remedio}, custa R$ 4,39.`);
  case `nimesulida`:
    console.log(`O produto ${remedio}, custa R$ 16,73.`);
  case `tadalafila`:
```

# Array
### Os arrays são usados para organizar e acessar dados relacionados de forma eficiente.
#### Atividade feita no CodePen
```js
Array

const livros = ["Javascript", "ECMAScript", "MongoDB", "Batman Piada Mortal", "Batman A queda do Morcego", "Batman que ri"]; 

console.log(livros[2]); 

 
let consulta = livros.indexOf("MongoDB");

```

# Função
### Sendo estruturas essenciais do código, as funções permitem definir um bloco de código reutilizável que pode ser executado muitas vezes dentro de um programa.
### Atividade feita no CodePen
```js
let min = prompt("digite o minimo:")
let max = prompt("digite o maximo:")

function aleatorio(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
console.log(aleatorio(min, max))

```


# Atividades
https://codepen.io/luis-Filipe-magno-gomes/pen/xxorZQr

https://codepen.io/luis-Filipe-magno-gomes/pen/oNroEZZ

https://codepen.io/luis-Filipe-magno-gomes/pen/WNqdYmr

https://codepen.io/luis-Filipe-magno-gomes/pen/wvVzGVG


