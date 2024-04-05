# Tipos Primitivos 

Um valor primitivo é um dado que não é representado através de um Objeto e, por consequência, não possui métodos, na maior parte do tempo, um valor primitivo é representado diretamente através do mais baixo nível da implementação de uma linguagem no JavaScript, existem 6 tipos primitivos:


### Booleean

Um booleano, em ciência da computação, é um tipo de dado lógico que pode ter apenas um de dois valores possíveis: verdadeiro ou falso. Por exemplo, em JavaScript, condicionais booleanas são usadas para decidir quais trechos do código serão executados ou repetidas.

Ex.
```javascript
let nota = 7.0
let situação = nota > 6.0 ? "aprovado" : "reprovado"
console.log(situação)
```

Crie uma funçao que volte ao usuario se ele é maior de idade ou não

```javascript
let idade = 18
let situação = idadew > 18 ? "maior de idade" : "menor de idade"
console.log(situação)
```

### Number

E um numero inteiro ou de ponto flutuante. Em outras linguagens de programação diferentes tipos numéricos podem existir, por exemplo: Integers (Inteiros), Floats (Pontos Flutuantes), Doubles (Dobros), ou Bignums.

Ex.
```javascript
var idade = 30;
var altura = 1.75;
```

Crie uma funçao que receba dois numeros e retorne a subtração deles.

```javascript
function main(a, b) {
    return a - b;
}
console.log(main)
```
### String 

Em JavaScript, uma String é um dos valores primitivos e o objeto String é um wrapper em cima do tipo primitivo string.

Ex.
```javascript
let ex = "Olá, Mundo!";
console.log(ex)
```

crie uma string e imprima ela na tela
```javascript
let ex = "STRING!";
console.log(ex)
```
### Undefined 

Um valor primitive automaticamente atribuido para variaveis que foram recentemente declaradas ou para arguments formais para qual não existem argumentos atualmente.

Ex.
```javascript
let variavel
console.log(variavel)
```
 
### Null

 Em ciência da computação, um valor nulo representa uma referencia que aponta, geralmente de maneira intencional, para um objeto ou endereço de memória inválido ou inexistente. O significado do valor nulo varia entre as implementações das linguagens.

```javascript
let variavel=null
console.log(variavel)

```

#Tipos de Dados

## Array
JavaScript não possui um tipo de dados array específico. No entanto, você pode usar o objeto predefinido Array e seus métodos para trabalhar com arrays em suas aplicações. O objeto Array tem métodos para manipular arrays de várias maneiras como join, reverse e sort.

Ex.
```javascript
var frutas = ["maçã", "banana", "laranja"];
var numeros = [1, 2, 3, 4, 5];
```

crie uma variavel que possa conter sttring e numeros inteiros


```javascript
var frutas = ["maria", "joao", "helena"];
var numeros = [1, 2, 3, 4];
```

## Objeto

O tipo de dado Object em JavaScript é usado para armazenar coleções de valores. Um objeto é uma estrutura de dados composta por um conjunto de propriedades, onde cada propriedade possui um nome e um valor associado. As propriedades podem ser acessadas utilizando a sintaxe de ponto ou a sintaxe de colchetes.

Ex.
```javascript
var pessoa = {
    nome: "Maria",
    idade: 25,
    cidade: "Lisboa"
};
```

crie uma variavel que contenha a raça de um cachorro sua idade e o nome de seu dono


```javascript
var pet = {
    nomecão : "Maria",
    idade: 25,
    dono: "Lisboa"
};
```