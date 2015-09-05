# Capítulo 2

## Iniciando com Java

Já que instalamos nossa JDK, *Java Development Kit*, e nosso editor de textos, vamos criar um diretório chamado *java_iniciante* e adicionar um arquivo chamado *PrimeiroPrograma.java* (Vou disponibilizar todos os aquivos criados aqui no repositório desse livro, recomendo desde já criar uma conta de usuário no [GitHub](http://github.com)), o nosso programa inicial terá uma estrutura como a seguinte:

```java
public class PrimeiroPrograma {

   /* Meu Primeiro programa em Java  
    * O velho Hello World que imprime Ola Mundo
    * na saida do console
    */
    
    public static void main(String []args) {
       System.out.println("Ola Mundo"); // imprime Ola Mundo
    }
}
```

Agora precisamos compilar o código fonte, ou seja, gerar aquele aquivo de *bytecode* que falamos no capítulo anterior e esse arquivo é que vai dizer à máquina virtual java o que estamos querendo que ela faça, nesse caso, imprimir a frase *Ola Mundo* no console (terminal). Como fazemos essa compilação? Basta chamar o compilador java, passando como parâmetro o aquivo em que está o nosso código fonte:

```
$ javac PrimeiroPrograma.java 
```

Após executar esse comando (lembrando que não precisa digitar o $, que só indica que é um terminal), note que será criado um novo arquivo como o mesmo nome mas com outra extensão, a extensão .class, arquivos .class são os *bytecodes* gerados pelo computador, para executar o nosso programa chamamos o java passando como parâmetro o nome do nosso programa:

```
$ java PrimeiroPrograma
Ola Mundo
```

Pronto! Nosso primeiro programa está funcionando e fazendo que pedimos para ele fazer, imprimir a frase "Ola Mundo" :D.

## Sintaxe Básica

Beleza, criamos o código, compilamos e executamos o programa gerado, mas o que são todas essas palavras que escrevemos no código para gerar esse programa? Bem, no Java, temos alguma regras que precisamos seguir para que o nosso programa possa ser compilado com sucesso, faça um teste, tire a palavra **main** do código do nosso primeiro programa e tente compilar novamente, você vai receber um erro conforme esse:

```
PrimeiroPrograma.java:8: error: <identifier> expected
    public static void (String []args) {
                      ^
1 error
```

Nosso compilador está informando que precisamos informar um identificador, que no caso é a palavra que retiramos. Todas essas regras chamamos de sintaxe.

### Palavras Reservadas

O java já tem algumas palavras defeinidas que não podemos utilizar para definir coisas que nos pertencem, como nome de variáveis, nomes de aqrquivos, etc, são elas:

| abstract | assert | boolean | break |
|byte|case|catch|char|
|class|const|continue|default|
|do|double|else|enum|
|extends|final|finally|float|
|for|goto|if|implements
|import|instanceof|int|interface|
|long|native|new|package|
|private|protected|public|return|
|short|static|strictfp|super|
|switch|synchronized|this|throw|
|throws|transient|try|void|
|volatile|while| | |
