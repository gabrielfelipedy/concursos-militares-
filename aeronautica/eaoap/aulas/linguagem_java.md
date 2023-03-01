### Introdução a aplicativos Java

<br>

<br>**O que é o Java?**<br>

Java é uma linguagem de programação criada pela Sun Microsystems, cujo principal objetivo era desenvolver uma linguagem que tivesse a portabilidade de rodar em qualquer dispositivo de pequeno porte e ao mesmo tempo ser multiplataforma

<br> 

<br>**Motivação:**<br>

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

[Praticar com exercícios](https://github.com/mathsstack/concursos-militares-/blob/main/aeronautica/eaoap/aulas/exercicios_introducao_java.md")

<br>

##


### Estruturas de Controle: if, if/else, while, for switch, do/while, break e continue

### Programação orientada a objetos

### Strings e Caracteres

### Tratamento de exceções: blocos try/catch, finally

### Multithreading: classe Thread, interface Runnable

### Arquivos e Fluxos

### Conectividade de banco de dados Java (JDBC). Servlets.
