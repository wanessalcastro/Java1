# Java1
console.log("Hello Word!")

var name = "Joao"
console.log (name)
let age = 25 //Escopo de bloco
console.log (age)
//Variavel que varia
const City = "São Paulo"
console.log (City)
//Sempre com um valor especifico pois nao pode ser alterada

//Tipos de Dados
name = "cachorro"
console.log(name)
age = "chocolate"
console.log(age)

let lastname = "Correa"
let heigh = 1.90 //Number
let isAproved = true //Boolean
let nothing = null //Null
let undefined //Undefined

//Type of -> descobrir o tipo da variável
console.log (typeof age)
console.log (typeof undefined)

//Operadores Matemáticos
let a = 5, b = 2
console.log(a, b) //5, 2

console.log(`${a} + ${b} = ${a + b}`)
console.log(`${a} - ${b} = ${a - b}`)
console.log(`${a} / ${b} = ${a / b}`)
console.log(`${a} * ${b} = ${a * b}`)
console.log(`${a} % ${b} = ${a % b}`) //Resto da Divisão(Módulo)
console.log(`${a} ** ${b} = ${a ** b}`) //Exponenciação

let i = 0
//Incremento
//pre
//i = i + i
console.log("pre", ++i)

//pos
console.log ("pos", i++)
console.log ("agora incrementou", i)

let x = 5
//Decremento
//pre
//x = x - 1
console.log("pre", --x)

//pos
console.log ("pos", x--)
console.log ("agora decrementou", x)

let y = 4
//Operação + atribuição
// y + y
y += 10
y -= 2
y /= 2
y *= 2
