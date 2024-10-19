# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

. Fundamentos do Javascript

. HTML


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
#### Atividade feita no CodePen
```js
let min = prompt("digite o minimo:")
let max = prompt("digite o maximo:")

function aleatorio(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
console.log(aleatorio(min, max))

```

# HTMl
### HTML é a sigla para HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto. É uma linguagem de programação que define a estrutura e o conteúdo das páginas da web.
#### Atividade feita no CodePen
```js
<nav>
  <ul>
    <li>
      <a href="">home</a>
    </li>
    <li>
      <a href="">sobre</a>
      </li>
    <li>
      <a href="">contato<a/>
        </li>
  </ul>
</nav>

<ul>
  <li>primeiro item.</li>
  <li>segundo item.</li>
  <li>terceiro item.</li>
</ul>







<html>
<head>
<title>Title of the document</title>
</head>
  

 
<body>
  
<header>
  <h1> MedioTec SENAC </h1>
</header> 
  
</body>

  
  
  
<main>
  
  
 <div>
   <p> Sobre Mim </p>
Me chamo Luis Filipe Magno Gomes, tenho 16 anos e atualmente estudo no mediotec na ala de desenvolvimento de sistema gosto de futebol e basquete amo jogare sou do signo de lanches meu de futebol e o sport e meu time no basquete e Golden State Warriors

  </div>
  
  <div>
    <p> habilidades </p>
    <li> Sei cozinhar.</li>
    <li> sei programar(mais ainda estou aprendendo).</li>
    <li> Sou engraçado </li>
    <li> Sei jorgar vidiogame </li>
    
    
    

  </div>
  
  
  <div>
    <p> Contatos </p>
   
  </div>
  
  
</main>
 
  
  <footer>
    <h2> Rodapé </h2>
  </footer>
  
  
  
  
  
  
  
</html>

```


# Atividades

## If else
https://codepen.io/luis-Filipe-magno-gomes/pen/xxorZQr

## switch case
https://codepen.io/luis-Filipe-magno-gomes/pen/oNroEZZ

## Array
https://codepen.io/luis-Filipe-magno-gomes/pen/WNqdYmr

## Função
https://codepen.io/luis-Filipe-magno-gomes/pen/wvVzGVG

## HTML
https://codepen.io/luis-Filipe-magno-gomes/pen/yLmJBPX

