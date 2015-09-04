# Capítulo 1

## O que é Java?

Java, como vocês já puderam supor, é uma linguagem de programação criada por James Gosling e inicalmente iria se chamar Oak, mas descobriu-se que já existia uma linguagem de programação com esse nome, foi então que os programadores que estavam desenvolvendo a linguagem a batizaram de Java em homenagem a uma cidade que é famosa por exportar café, já que esse produto foi o mais consumido durante o projeto, até hoje é assim, a maioria dos programadores só funciona com uma máquina de café do lado.

A linguagem Java é baseada em outras linguagens como C/C++ dentre outras, é uma linguagem parcialmente compilada e parcialmente interpretada que em sua compilação gera um arquivo que é entendido por qualquer outro sistema que possua uma máquina virtual Java instalado, ou seja, não é necessário escrever uma aplicação para cada sistema. O arquivo gerado por essa compilação é chamado de bytecode, esse fato de escrever uma vez e rodar onde quiser fez do Java uma das linguagens mais utilizadas no mundo.

Java é utilizado amplamente no mundo e para os diversos propósitos como sistemas web, stand-alone, mobile, etc.

## O que vamos precisar?

Sem muito blá blá blá, veremos o que precisaremos para começar a desenvolver nossas aplicações em Java. Primeiro precisaremos fazer o download do Kit de Desenvolvimento Java no site da Oracle [aqui](http://www.oracle.com/technetwork/pt/java/javase/downloads/jdk8-downloads-2133151.html). Faça o download de acordo com o seu sistema operacional, seguem as instruções de instalação para os principais:

* [Linux](http://lmgtfy.com/?q=Como+instalar+java+jdk+no+Linux)
* [Mac Os X](http://lmgtfy.com/?q=Como+instalar+java+jdk+no+Mac)
* [Windows](http://lmgtfy.com/?q=Como+instalar+java+jdk+no+Windows)

Pronto! Depois de instalado só utilizar um editor de textos qualquer para começar a escrever as nossas aplicações, eu recomendo fortemente o uso de um dos seguintes editores [Sublime Text](sublimetext.com) (Esse é pago mas tem uma versão de avaliação - Muito Bom!), [Notepad++](https://notepad-plus-plus.org/) (Grátis!) ou o [Atom](https://atom.io/) (Muito bom também - Grátis). O uso desses editores facilitarão o nosso trabalho porque ele marca o nosso código de formar que podemos diferenciar o que estamos escrevendo, exemplo:

```java
public class ExemploLivro{
   public static void main(String args[]){
      String str = "Hello World";
      String anotherString = "hello world";
      Object objStr = str;

      System.out.println( str.compareTo(anotherString) );
      System.out.println( str.compareToIgnoreCase(anotherString) );
      System.out.println( str.compareTo(objStr.toString()));
   }
}
```

Não precisa se assustar com o código, depois explico! Mas podemos observar que algumas palavras estão com cores diferentes, são palavras reservadas Java, nomes de arquivos, sequencias especiais de texto e etc. Assim facilita o nosso trabalho, outra ferramenta que irá facilitar o nosso trabalho são as IDE's (Ferramentas Integradas de Desenvolvimento), mas isso é assunto pra depois, vamos começar do começo que é o certo :).
