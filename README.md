# aula-10
// Exercicio 1

let nome = prompt("qual seu nome"); 
let cor = prompt("qual sua cor favorita");

console.log("a cor favorita de " + nome + " e " + cor);
console.log("a cor favorita de $ {nome} e ${cor}");
/*
// retornar o numero de caracteres em uma string;
console.log(nome.legth);

// retornar a string convertida para minusculo;
console.log(nome.toLowerCase());

//retornar a string convertida para maiusculo;
console.log(nome.toUpperCase());

// retira os espaços ao redor da string/
console.log(nome.trim);
 
// metodo para buscar determinado texto dentro de uma string;
console.log(nome.includes ("cenoura"));

// troca o texto da string pelo texto fornecido;
// //replaceAll("texto antigo" ,"texto novo")
console.log(nome.replaceAll("cenoura", "batata"));
*/

//exercicio 2
let frase = prompt("Escreva uma frase");
console.log(frase.toUpperCase());

console.log(frase.toUpperCase());
console.log(frase.replaceAll("o" , "i"));
console.log(frase.legth);

//arrays
/*
let listaDeExercicio = {"elevaçao lateral" ,"supino" ,"voador"};
console.log(listaDeExercicios{0});
console.log(listaDeExercicios{1});
console.log(listaDeExercicios{2});
*/

// Exercicio 3

let listaDeCachorro = ["buldogue,pastor alemao ,labrador, rottweiler,pug"];
let numero = Number (prompt ("Digite um numero 0 a 4"));
console.log(cachorro[numero]);
/*
const pokemon = ["bulbasauro", "squirtle","chamader"];
console.log(pokemon.legth);
console.log(pokemom[0].legth);
*/

/*
const seriesBoas = ["Breakiing","Bad", "Brooklyn Nine-nime"];
comsole.log(seriesBoas.includes("Breaking Bad"));
console.log(series.inclides("Game og Trones")); // false
*/
 
let instrumento = ["violao", "guitarra", "bateria",];
console.log(instrumento);
instrumento;push("teclado");
console.log(instrumento);
instrumento.pop();
console.log(instrumento);


//Exercicio 4
let valores  = [1,2,3,4,5,6];
console.log(valores);
console.log(valores.length);
valores.push(7);
console.log(valores);
valores.splice(3,2);
console.log(valores.length);
