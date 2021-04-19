# Ejercicios de JavaScript

Esta es una lista de 100 ejercicios de JavaScript para personas que están empezando con programación. Para hacer estos ejercicios deberás conocer los siguientes conceptos: tipos y operadores, variables, condicionales, ciclos, strings, arreglos, funciones y objetos literales. Si aún no los conoces te recomendamos primero ver [los videos de esta lista en YouTube](https://www.youtube.com/playlist?list=PLxyfMWnjW2kvB-INxVmGBjdqdCjxOjV8A). 

## Ejercicio 1 - Contraseña válida

Escribir una función llamada `contrasenaValida` que reciba un string y retorne `true` si el string es igual a "2Fj(jjbFsuj" o "eoZiugBf&g9". De lo contrario debe retornar `false`.

```javascript
// escribe tu respuesta acá

console.log("2Fj(jjbFsuj") // true
console.log("eoZiugBf&g9") // true
console.log("hola") // false
console.log() // false
```

## Ejercicio 2 - Calcular impuestos

Escribir una función llamada `calcularImpuestos` que reciba dos argumentos numéricos: `edad` e `ingresos`. Si `edad` es igual o mayor a 18 y los ingresos son iguales o mayores a 1000 debe retornar `ingresos` * 40%. De lo contrario retornar 0.

```javascript
// escribe tu respuesta acá

console.log(18, 1000) // 400
console.log(40, 10000) // 4000
console.log(17, 5000) // 0
console.log(30, 500) // 0
```

## Ejercicio 3 - IMC (ïndice de masa corporal)

El índice de masa corporal (IMC), o BMI por sus siglas en inglés, es un valor que determina la cantidad de grasa de una persona.

El BMI se calcula con la siguiente formula: `peso / altura^2`

Escribir una función llamada `bmi` que reciba dos argumentos: peso y altura, y retorne un string con las siguientes posibilidades:

* "Bajo de peso" si el BMI < 18.5
* "Normal" si está entre 18.5 y 24.9
* "Sobrepeso" si está entre 25 y 29.9
* "Obeso" si es igual o mayor a 30

```javascript
// escribe la función bmi acá

// código de prueba
console.log(bmi(65, 1.8)) // "Normal"
console.log(bmi(72, 1.6)) // "Sobrepeso"
console.log(bmi(52, 1.75)) //  "Bajo de peso"
console.log(bmi(135, 1.7)) // "Obeso"
```

## Ejercicio 4 - Imprimir un arreglo

Escribir una función llamada `imprimirArreglo` que reciba un arreglo e imprima cada elemento en una línea a parte:

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(imprimirArreglo(1, "Hola", 2, "Mundo"))
// 1
// Hola
// 2
// Mundo
```

## Ejercicio 5 - Número de Likes

Escribe una función llamada `likes` que reciba un número y retorne un string utilizando el formato de K para miles y M para millones.

Por ejemplo:

* 1400 se convierte en 1K
* 34,567 se convierte en 34K
* 7’456,345 se convierte en 7M.

Si el número es menor a 1000 se debe devolver el mismo número como un string.

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(likes(983)) // "983"
console.log(likes(1900)) // "1K"
console.log(likes(54000)) // "54K"
console.log(likes(120800)) // "120K"
console.log(likes(25222444)) // "25M"
```

## Ejercicio 6 - FizzBuzz

Escribir una función llamada `fizzBuzz` que reciba un número y retorne un string de acuerdo a lo siguiente:

* "fizz" si el número es múltiplo de 3.
* "buzz" si el número es múltiplo de 5.
* "fizzbuzz" si el número es múltiplo tanto de 3 como de 5.
* Si no cumple ninguna de las condiciones anteriores debe retornar el mismo número.

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(fizzBuzz(6)); // "fizz"
console.log(fizzBuzz(20)); // "buzz"
console.log(fizzBuzz(30)); // "fizzbuzz"
console.log(fizzBuzz(8)); // 8
```

## Ejercicio 7 - Número de aes (letra "a")

Escribir una función llamada `numeroDeAes` que reciba un string y retorne el número de veces que aparece la letra "a":

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(numeroDeAes("abracadabra")) // 5
console.log(numeroDeAes("etinol")) // 0
console.log(numeroDeAes("")) // 0
```

## Ejercicio 8 - Número de caracteres

Escribir una función llamada `numeroDeCaracteres` que reciba un string y un caracter (un string de un caracter). La función debe retornar el número de veces que aparece el caracter en el string.

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(numeroDeCaracteres("Hola Mundo", "o")) // 2
console.log(numeroDeCaracteres("MMMMM", "m")) // 0
console.log(numeroDeCaracteres("eeee", e)) // 4
```

## Ejercicio 9 - Sumar arreglo

Escribir una función llamada `sumarArreglo` que reciba un arreglo de números y retorne la suma de todos los elementos.

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(sumarArreglo([3, 1, 2])) // 6
console.log(sumarArreglo([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])) // 55
console.log(sumarArreglo([])) // 0
```

## Ejercicio 10 - Multiplicar arreglo

Escribir una función llamada `multiplicarArreglo` que reciba un arreglo de números y retorne la multiplicación de todos los elementos.

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(multiplicarArreglo([4, 1, 2, 3])) // 24
console.log(multiplicarArreglo([1, 2, 3, 4, 5, 6, 7, 8])) // 40320
console.log(multiplicarArreglo([])) // 1
```

## Ejercicio 11 - Remover ceros

Escribir una función llamada `removerCeros` que reciba un arreglo de números y retorne un nuevo arreglo excluyendo los ceros (0).

```javascript
// escribe tu respuesta acá

// código de prueba
console.log(removerCeros([0, 1, 0, 2, 0, 3])) // [1, 2, 3]
console.log(removerCeros([9, 3, 6, 4])) // [9, 3, 6, 4]
console.log(removerCeros([0, 0, 0])) // []
```
