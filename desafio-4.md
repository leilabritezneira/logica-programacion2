# Resolución de los desafíos del curso de lógica de programación <h1>

Practicar la lógica de programación, incluyendo conceptos como variables, condiciones (if-else), bucles (while) e interacciones con el usuario (alert, prompt), es esencial para tu carrera en el desarrollo de software. Estos fundamentos son la base para abordar problemas de manera estructurada, tomar decisiones sin código, crear bucles controlados e interactuar de manera efectiva con los usuarios.

Comprender estos conceptos no solo facilita el aprendizaje de nuevos lenguajes y tecnologías, sino que también te capacita para crear soluciones innovadoras, depurar de manera eficiente y mantener la calidad a lo largo del ciclo de vida del software. Por lo tanto, invertir tiempo en estos principios desde temprano es fundamental para construir una base sólida y exitosa en el campo de la programación.

## Desafíos - Respuestas <h2>

1. Crea un programa que utilice console.log para mostrar un mensaje de bienvenida.
```javascript
console.log('Bienvenido');
```
2. Crea una variable llamada "nombre" y asígnale tu nombre. A continuación, utiliza console.log para mostrar el mensaje "¡Hola, [tu nombre]!" en la consola del navegador. 
```javascript
let nombre = 'Leila';
console.log(`Hola, ${nombre}!`);
```
3. Crea una variable llamada "nombre" y asígnale tu nombre. A continuación, utiliza alert para mostrar el mensaje "¡Hola, [tu nombre]!". 
```javascript
let nombre = 'Leila';
alert(`Hola, ${nombre}!`);
```
4. Utiliza el prompt y formula la siguiente pregunta: ¿Qué lenguaje de programación te gusta más? A continuación, almacene la respuesta en una variable y muéstrela en la consola del navegador. 
```javascript
let lenguajePreferido = prompt('¿Qué lenguaje de programación te gusta más?');
console.log(lenguajePreferido);
```
5. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. A continuación, suma estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza console.log para mostrar en la consola el mensaje "La suma de [valor1] y [valor2] es igual a [resultado]". 
```javascript
let valor1 = 42;
let valor2 = 8;
let resultado = valor1 + valor2;

console.log(`La suma de ${valor1} y ${valor2} es igual a ${resultado}.`)
```
6. Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. A continuación, resta estos dos valores y almacena el resultado en una tercera variable llamada "resultado". Utiliza console.log para mostrar en la consola el mensaje "La diferencia entre [valor1] y [valor2] es igual a [resultado]". 
```javascript
let valor1 = 10;
let valor2 = 8;
let resultado = valor1 - valor2;

console.log(`La diferencia entre ${valor1} y ${valor2} es igual a ${resultado}.`);
```
7. Pida al usuario que introduzca su edad en la pantalla. Basándose en la edad introducida, utilice un if para comprobar si la persona es mayor o menor de edad, mostrando un mensaje apropiado en la consola. 
```javascript
let edad = prompt('Digite su edad:');
if (edad > 17) {
    console.log('Usted es mayor de edad.');
} else {
    console.log('Usted es menor de edad.');
}
```
8. Crea una variable "número" y pídele un valor con el prompt comprueba si es positivo, negativo o cero. Utilice if-else para imprimir el mensaje correspondiente. 
```javascript
var numero = parseFloat(prompt("Digite un número:"));

if (numero > 0) {
    console.log("El número es positivo.");
} else if (numero < 0) {
    console.log("El número es negativo.");
} else {
    console.log("El número es cero.");
}
```
9. Utiliza un bucle while para imprimir los números del 1 al 10 en la consola. 
```javascript
let numero = 1;
while (numero <= 10) {
    console.log(numero);
    numero++;
}
```
10. Crea una variable "nota" y asígnale un valor numérico. Utilice if-else para determinar si la nota es mayor o igual que 7 y muestre "Aprobado" o "Reprobado" en la consola. 
```javascript
let nota = 8; // Ejemplo del valor de la nota que se desea probar

if (nota >= 7) {
    console.log("Aprobado");
} else {
    console.log("Reprobado");
}
```
11. Utiliza Math.ramdon para generar cualquier número aleatorio y mostrarlo en la consola. 
```javascript
let numeroAleatorio = Math.random();
console.log(numeroAleatorio);
```
12. Utilice Math.ramdon para generar un número entero entre 1 y 10 y mostrar este número en la consola. 
```javascript
let numeroEnteroAleatorio = parseInt(Math.random() * 10) + 1;
console.log(numeroEnteroAleatorio);
```
13. Utilice Math.ramdon para generar un número entero entre 1 y 1000 y mostrar este número en la consola. 
```javascript
let numeroEnteroAleatorio = parseInt(Math.random() * 1000) + 1;
console.log(numeroEnteroAleatorio);
```