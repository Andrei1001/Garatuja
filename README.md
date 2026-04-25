# Garatujas - Andrei Diz Schmitt

Html:lingugem de texto onde serve como corpo principal "esquelto para o site"
CSS: Serve como o a "pele" ou "maquiagem do site"
JS: Serve para fazer o site funcionar9lingugame de programação).

====================================================================================================================================================================================================================


Diferenças entre Java, JS (JavaScript) e TS (TypeScript)



JAVA
Linguagem compilada (gera bytecode que roda na JVM)
Tipagem forte e estática (você precisa declarar tipos)
Muito usada em:
Sistemas grandes (empresas)
Backend
Apps Android (principalmente antigos)
Paradigma principal: Orientado a Objetos

JS
Linguagem interpretada (roda direto no navegador ou no Node.js)
Tipagem dinâmica (não precisa declarar tipo)
Usada em:
Frontend (sites)
Backend com Node.js
Mais flexível (mas pode gerar erros mais fáceis)

TS
É um "superconjunto" do JavaScript (JS com melhorias)
Tipagem estática opcional
Precisa ser compilado para JavaScript
Muito usado em:
Projetos grandes
Frameworks modernos (React, Angular, etc.)

====================================================================================================================================================================================================================

Classe
“Molde” para criar objetos
Define atributos e métodos
Exemplo: classe Carro

 Objeto
Instância de uma classe
É o “objeto real” criado a partir do molde
Exemplo: meuCarro = new Carro()

Atributo
Variáveis da classe
Guardam características do objeto
Ex: cor, idade, nome

 Método
Funções dentro da classe
Definem comportamentos
Ex: acelerar(), falar(), calcular()

 Getters e Setters
Métodos para acessar e modificar atributos
Getter → pega valor
Setter → altera valor

Usados para controle e segurança
 Construtor
Método especial executado ao criar o objeto
Serve para inicializar valores
Ex: definir nome ou idade ao criar

 Herança
Uma classe pode herdar de outra
Reutiliza código
Ex: Cachorro herda de Animal

Encapsulamento
Protege os dados da classe
Usa modificadores (private, public, etc.)
Acesso controlado via getters/setters

Polimorfismo
Um método pode ter vários comportamentos
Mesmo nome, ações diferentes
Ex: animal.fazerSom() → cada animal faz um som diferente

====================================================================================================================================================================================================================

O que é POO (Programação Orientada a Objetos)?

POO é um jeito de programar baseado em objetos, ou seja, você organiza o código como se fosse coisas do mundo real.

PERGUNTAS:

Como funciona o Private, Public e Protected ?

Public
Pode ser acessado de qualquer lugar
Dentro e fora da classe
É o padrão em muitas linguagens

Private
Só pode ser acessado dentro da própria classe
Não é visível fora dela
Usado para proteger dados

Acesso limitado
Pode ser acessado:
Dentro da classe
Por classes filhas (herança)


Como funciona o this.

Palavra-chave que representa o próprio objeto atual
Usada dentro de classes e objetos
Permite acessar atributos e métodos do próprio objeto
Diferenciar variáveis locais de atributos
Acessar dados do próprio objeto
Chamar métodos da mesma classe


Get vs Set (diferenças).

 Getter (get)
Método usado para obter (ler) o valor de um atributo
Normalmente não altera nada
Retorna um valor
Usado para acesso controlado a atributos privados

Setter (set)
Método usado para definir (alterar) o valor de um atributo
Pode ter validações antes de mudar o valor
Geralmente não retorna nada (void)

====================================================================================================================================================================================================================

const srv = Bun.serve({
    port: 8080,
    routes: {
        "/goku": () => new Response(         
            `<a href='https://www.reddit.com/r/brasilivre/comments/klpyrk/goku_careca/'>clica</a> `, 
            { headers: { "Content-Type": "text/html"}}
        )
    }
    , fetch(request) {
        return new Response("OLA", {headers: {'content-Type': "text/html"}})
    }

}) 
    
