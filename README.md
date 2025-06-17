# JavaScript

##                                                  PARTE 1
### 1.1  
JavaScript es un lenguaje de programación que permite darle funcionalidad e interactividad a las páginas web, permitiendo tanto efectos visuales mas potentes, como funcionalidades por parte del servidor como por ejemplo enviar información a bases de datos o consumir APIs.

1.2 
Es un lenguaje de alto nivel, permite la manipulacion del DOM, es versátil porque permite funcionalidades tanto de back, como front.

1.3 Que JavaScript sea un lenguaje interpretado significa que no tiene que ser compilado, sino que es interpretado directamente por el navegador, que esté basado en eventos significa que es receptivo a las acciones del usuario para desencadenar una serie de eventos de forma interactiva, por ejemplo que muestre un mensaje al darle click a un botón.

##                                                  PARTE 2
### 2.1 ```js
let nombre = 'Santiago'
console.log(`Hola, yo soy ${nombre}`)

2.2 let entero = 20;
let decimal = 20.20;
let lastName = 'Villa';
console.log(`El numero entero es ${entero}, el decimal es ${decimal} y el apellido es ${lastName}`)

2.3 Cada vez que se asigna un valor para la variable, este se sobreescribe y por lo tanto me toma el ultimo valor asignado

2.4 El mensaje que se muestra es "undefined", como si no existiera

2.5 La variable con valor null muestra en consola "null" y la que tiene valor booleano muestra dicho valor

                                                  PARTE 3

3.1 let age = prompt('Cual es tu edad?')  
console.log(`Tienes ${age} años`)

3.2 alert('Welcome to the jungle!')

3.3 confirm('Deseas continuar?')

                                                  PARTE 4

4.1 let num1 = 20
let num2 = 45

let result = num1 + num2
console.log(result)

result = num1 - num2
console.log(result)

result = num1 * num2
console.log(result)

result = num1 / num2
console.log(result)

result = num1 % num2
console.log(result)

4.2 let string1 = 'Hola, bienvenido'
let string2 = '¿Cómo estás?'

console.log(string1 + string2)

4.3 console.log(5 == "5")  //True
console.log(5 === "5")  //False
console.log(true && false)  //False
console.log(false || true)   //True
console.log(!true)   //False

                                                  PARTE 5

5.1 let num = prompt('Ingresa un número')

if (num < 10) {
    console.log(`El número ingresado "${num}" es menor a 10`)
} else if (num == 10) {
    console.log(`El número ingresado "${num}" es igual a 10`)
} else if (num > 10) {
    console.log(`El número ingresado "${num}" es mayor a 10`)
} else {
    console.log('Error, ingresa un número')
}

5.2 let name = prompt('Please enter the name of the user')

if (name.toLowerCase() == 'admin') {
    alert('Bienvenido admin!')
} else {
    alert('Bienvenido!')
}

5.3 let num = prompt('Please enter a number')

let isPair = num % 2 == 0 ? 'is pair' : 'is not pair'

console.log(`The number ${num} ${isPair}`)


                                                  PARTE 6

6.1 
console.info('This is an informative message')

console.warn('This is a warning message')

console.error('This is an error message')

console.group('User info')
console.log('Name: Santiago')
console.log('Last name: Villa')
console.group('Contact info')
console.log('Email address: santiagovillapanesso1@gmail.com')
console.log('Phone number: 3193418511')
console.groupEnd()
console.group('Family info')
console.log('Lives with: Mom, Dad, Cousin')
console.log('Siblings: none')
console.groupEnd()
console.groupEnd()

console.time('Bucle_time')
let num = 20
for (let i = 0; i < 10000; i++) {
    num *= i
}
console.timeEnd('Bucle_time')

                                                  PARTE 7

/*This method quantifies the time it takes a specific block of code to be executed from the declaration of console.time until the console.timeEnd declaration */
console.time('Bucle_time')
let num = 20
for (let i = 0; i < 10000; i++) {
    num *= i
}
console.timeEnd('Bucle_time')
