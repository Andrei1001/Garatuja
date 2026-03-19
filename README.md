# Garatujas - Andrei Diz Schmitt

HTML: Html é uma linguagem de marcação, onde ele serve para estrutuar o site.

Css: Css serve para dar uma "maquiagem" para o site. Ele é quem faz a interface para o site.


#Js (JavaScript) vs Ts(Type Scipt) Vs Jv(Java)

COMO CRIAR UMA FUNÇÃO
 
 JS: Para criar uma função em JavaScript, utilize a palavra-chave function, seguida de um nome, parênteses () para parâmetros opcionais e chaves {} para o corpo da função. A lógica é colocada dentro das chaves e a função pode retornar um valor com return.

// Exemplo: Função de soma
function somar(a, b) {
  return a + b;
}

// Como chamar a função
let resultado = somar(5, 3); // Retorna 8
console.log(resultado);


TS:Para criar uma função em TypeScript, defina o nome, os tipos dos parâmetros e o tipo de retorno, utilizando function ou arrow functions () => {}. A sintaxe principal exige (parametro: tipo): tipoRetorno. O compilador verifica erros de tipo automaticamente.


// Exemplo de função tradicional
function somar(a: number, b: number): number {
  return a + b;
}

// Exemplo de Arrow Function
const subtrair = (a: number, b: number): number => a - b;

console.log(somar(5, 3)); // Saída: 8

Jv:Para criar uma função (método) em Java, defina seu modificador de acesso (ex: public), tipo de retorno (ex: void ou int), nome, parâmetros entre parênteses e o bloco de código {}. Métodos devem ter responsabilidade única e, preferencialmente, serem descritivos, como public int somar(int a, int b) { return a + b; }.

modificadorRetorno nomeDaFuncao(parametros) {
    // Corpo do método
    // return valor; // Necessário se não for void
}


JS:
FUNCTION
function saudar() {
    console.log("Olá, bem-vindo!");
}
Method

variable
attribute /fazer depois/


