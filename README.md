# PRACTICA-3-LUZ-ARANDA-
Después separar la frase por las comas e imprimir cada palabra, así como la longitud de la cadena final.

/*
19070693-LUZ MIG DALIA LOREDO ARANDA - LenguajesY Automatas II
PRACTICA 3
*/
var cadena = "Hola,mucho,gusto,bienvenido,al,Instituto,Tecnologico,de,San,Luis,Potosi,Capital";
const espacio= ' ';
var cadenaremp = cadena.replaceAll(",", " ");

console.log(cadenaremp);
console.log("Tamano cadena: ",cadenaremp.length);

