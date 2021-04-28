# Funções

```java
public static void main(String[] args) {
   System.out.print("Olá menu nome é Gustavo");
}
```

# Variáveis

```java
public static void main(String[] args) {
   int idade = 20;
   double dinheiro = 10.50;
   String nome = "Gustavo";

   System.out.print("Olá menu nome é ");
   System.out.print(nome);
   System.out.print(" ganho ");
   System.out.print(dinheiro);
   System.out.print(" e tenho ");
   System.out.print(idade);
   System.out.print(" anos ");

}
```

# Operadores Aritméticos

```
   +	Adição
   –	Subtração
   *	Multiplicação
   /	Divisão
   %	Módulo (é o resto da divisão)
```

```java
public static void main(String[] args) {
        int numberOne = 20;
        int numberTwo = 20;

        System.out.print("Soma: ");
        System.out.println(numberOne+numberTwo);

        System.out.print("Subtração: ");
        System.out.println(numberOne-numberTwo);

        System.out.print("Multiplicação: ");
        System.out.println(numberOne*numberTwo);

        System.out.print("Divisão: ");
        System.out.println(numberOne/numberTwo);

        System.out.print("Módulo: ");
        System.out.println(numberOne%numberTwo);
    }
```

# Operadores Condicionais

```
   ||	OR dinâmico
   &&	AND
   ^	XOR
   !	NOT
```

# Operadores Relacionais

```
   ==	igual a
   !=	Diferente de
   >	Maior que
   <	Menor que
   >=	Maior ou igual a
   <=	Menor ou igual a
```

# Estruturas Condicionais
```java
   public static void main(String[] args) {
      int resposta = 10;
      if (resposta == 10) { 
         System.out.println(“A resposta é exatamente 10!”);
      } else if (resposta > 10) {
         System.out.println(“A resposta é maior que 10!”);
      } else {
         System.out.println(“A resposta é menor que 10!”);
      }
   }
```
# Estruturas De Repetição
## While
O termo while pode ser traduzido para o português como “enquanto”. Este termo é utilizado para construir uma estrutura de repetição que executa, repetidamente, uma única instrução ou um bloco delas “enquanto” uma expressão booleana for verdadeira.
```java
   public static void main(String[] args) {
      int contador = 10;
      while(contador < 10){
         System.out.println(“Não atingiu 10!”);
         contador++;
      }
   }
```
## Do-while
A estrutura de repetição do-while é uma variação da estrutura while. Existe uma diferença sutil, porém importante, entre elas. Em um laço while, a condição é testada antes da primeira execução das instruções que compõem seu corpo.
```java
   public static void main(String[] args) {
      int contador = 10;
      do{
         System.out.println(Já atingiu 10!”);
         contador++;
      } while(contador < 10);
   }
```
## For
O laço for é uma estrutura de repetição compacta. Seus elementos de inicialização, condição e iteração são reunidos na forma de um cabeçalho e o corpo é disposto em seguida.
For e While são apenas formas diferentes de uma mesma estrutura básica de repetição. Qualquer laço for pode ser transcrito em termos de um laço while e vice-versa. Do mesmo modo que em um laço while, se a condição de um laço for já é falsa logo na primeira avaliação que se fizer dela, as instruções contidas em seu corpo jamais serão executadas.


```java
   public static void main(String[] args) {
      for(int contador = 0; contador < 1000; x++){
         System.out.println("Repetiu até ser menor que 1000");
      }
   }
```



### Referência

- https://cursojavanow.com.br/category/artigos/
- https://www.treinaweb.com.br/
- https://tableless.com.br/
