### Introdução a aplicativos Java

<br>

<br>:question: **O que é o Java?**<br>

Java é uma linguagem de programação criada pela Sun Microsystems, cujo principal objetivo era desenvolver uma linguagem que tivesse a portabilidade de rodar em qualquer dispositivo de pequeno porte e ao mesmo tempo ser multiplataforma

<br> 

<br>:bulb: **Motivação:**<br>

A maioria das linguagens compiladas na época em que o Java era inexistente (A linguagem C, por exemplo) possuia um problema na parte da dinâmica dos programas.
Isso porque para executar um código fonte C em várias plataformas era necessário compilar o código uma vez para cada plataforma a ser utilizada.

Com a chegada do Java. Foi possível solucionar essa questão através da inserção de uma máquina virtual (a JVM) para cada OS diferente. Assim, um mesmo código compilado não precisaria ser recompilado para rodar em outras plataformas. Pois o bytecode Java é universal e a própria JVM gerencia a sua execução 

<br>

<br>**Primeiro programa em Java**<br>

<br>

Vamos começar com o clássico "Olá mundo" que todo mundo aprende ao programar pela primeira vez!

Para imprimir "Olá mundo" na tela usaremos o seguinte código:

```java
System.out.println("Olá Mundo");
```

Observe atentamente as letras maiúsculas e minúsculas, parêntese, aspas e ponto e vírgula!
Java é uma linguagem fortemente tipada, ou seja, existem algumas regrinhas que precisam ser seguidas na hora de digitar o seu código.

No entanto. Só isso não é suficiente para o Java. Precisamos criar um ambiente perfeito pro código rodar corretamente. Não podemos deixar ele solto na aplicação:

Basicamente precisamos criar uma classe com um método principal ou método main (Não se preocupe com a nomenclatura. Em breve tudo será melhor entendido!

O código completo fica assim:

```java
class OlaMundo {
     public static void main(String[] args) {
          System.out.println("Olá mundo");
     }
}

```
##

:memo: [Praticar com exercícios](https://github.com/mathsstack/concursos-militares-/blob/main/aeronautica/eaoap/aulas/exercicios_introducao_java.md)

<br>

##


## Estruturas de Controle: if, if/else, while, for switch, do/while, break e continue

Em várias linguagens de programação é essencial que alguns códigos não sejam sempre exceutados. Mas somente se acontecer algo definido na aplicação 
No Java não é diferente. Possuímos estruturas que auxiliam o nosso programa a funcionar da forma correta e a tomar decisões 


Podemos divir as estruturas de controle em dois grupos:

* Estruturas condicionais 

> Recebem uma condição é só executam o bloco ligado a elas se essa condição for verdadeira

* Estruturas de repetição 

> Repetem um bloco de código um número definido de vezes ou seguindo uma condição específica 

##

Vamos aprender a usar cada uma delas:

### Estruturas condicionais:

##

No Java temos 3 estrutura condicionais:

* if
* if/else
* switch/case

O if (do inglês: "se") executa um código se a condição passada a ele por parâmetro for verdadeira

Ex: o código a seguir verifica se uma pessoa é maior de 18 anos:

```java

int idade = 18;

if(idade >= 18) {

    System.out.println("É maior de idade");
}

```

Observe que a mensagem "É maior de idade" só é imprimida se a idade for maior ou igual a 18. Esse código agora não executa sempre, mas depende da validação de uma condição 

No entanto, nosso programa não mostra nada se o indivíduo não é maior de idade. Podemos corrigir isso adicionando o else (do inglês: "se não "). Ao contrário do if. O conteúdo que estiver dentro do else só excecuta se a condição que estiver no if for falsa

Por exemplo: Queremos validar a entrada de uma pessoa em uma festa. Vamos deixar a pessoa ou não dependendo da sua idade:

```java

int idade = 16;

if(idade >= 18) {

    System.out.println("Pode entrar");

} else {

    System.out.println("Não pode entrar");
}

```

Agora temos dois blocos de código em que apenas ou um ou outro é excecutado. Nunca os dois ao mesmo tempo.

A nossa última estrutura, o switch-case, é um modo mais elegante de escrever vários ifs sequencias:

Por exemplo: imagine que queremos mover um personagem em um jogo. Em código seria assim:

```java
char comando = 'a';

if(comando == 'a') {

     jogador.mover(esquerda);

} else if(comando == 'w') {

    jogador.mover(cima);

} else if(comando == 's') {

    jogador.mover(baixo);

} else if(comando == 'd') {

    jogador.mover(direita);

}
```

Perceba que ficar repetindo muitos ifs tira a estética do código e pode gerar futuras dores de cabeça com implementação. Assim, podemos fazer um switch-case deixando o código assim:

```java
char comando = 'a';

switch(comando) {

    case 'a' : jogador.mover(esquerda);
    case 'w' : jogador.mover(cima);
    case 's' : jogador.mover(baixo);
    case 'd' : jogador.mover(direita);
}

```

### Estruturas de repetição 

Imagine que queremos criar um programa que imprime uma tabuada. A implementação seria mais ou menos assim:

O programa rodará normalmemte. Mas perceba como o código está muito repetitivo. Temos a mesma estrutura padrão modificando apenas o multiplicador e o resultado. Poderíamos fazer isso de um jeito mais simples?

Podemos sim. Para isso usaremos estruturas de repetição

Em Java possuímos três estruturas básicas: for, while e do-while. Nesse caso usaremos o for

A sintaxe do for é a seguinte:

Codigo

Caso queriamos saber o comportamento desse "i". Fazemos:

Codigo

Ou seja. A cada vez que o laço se repetir. O valor de i será diferente e usaremos isso a nosso favor pra refazer a noss a tabuada:

Código 

Tudo bem mais elegante e legível!!

Exercícios


## Programação orientada a objetos

## Strings e Caracteres

## Tratamento de exceções: blocos try/catch, finally

## Multithreading: classe Thread, interface Runnable

## Arquivos e Fluxos

## Conectividade de banco de dados Java (JDBC). Servlets.
