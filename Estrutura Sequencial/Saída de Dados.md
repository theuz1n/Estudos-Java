
A saída de dados consiste em quando o programa informa dados aos usuários, também conhecida como escrita.

**sem quebra de linha no final**
```java
System.out.print("olá mundo");
```
**com quebra de linha no final**
``` java
System.out.println("olá mundo");
```
**Saída de variável do tipo ponto flutuante**
``` java
a double =  32.50;

System.out.printf("%.2f", a);
```
veja no exemplo acima que após o `%`. você ira dizer qual será a quantidade de casas decimais a ser mostradas depois da vírgula. Use o `%n` ou `\n` para quebra de linha no final.

### Concatenação de Vários Elementos

faz-se uso do 
```java 
println()
``` 
ou do `print` onde funciona da seguinte maneira: _elemento1+elemento2+....+elementoN_.

Ex:  
```java
String pessoa = João;
System.out.println("oi "+pessoa+"tudo bem");
```

para concatenar elementos de vários tipos faz uso dos seguintes marcadores:

`%f-pontos flutuantes`

`%d- inteiro`

`%s - texto`

`%n - quebra de linha`

**Regra geral para printf**

coloca-se as variáveis na sequencia que foi escrita as suas marcações.
( "texto1 %f texto2 %f texto3 %f",t1,t2,t3)
Ex:  
```java
System.out.printf("Resultado = %.2f metros %n",x);
```

### Uso do Locale

A função locale no Java nada mais é que uma forma de configurar o parâmetro de qual nacionalidade será usado para a entrada e saída dos dados.

Ex: por padrão vem-se no modelo local da maquina, caso venha diferente pode-se usar inscrever o seguinte código 
```java
 Locale.setDefault(Locale.getDefault());
 ```
Para se escolher um modelo local utilize o 
```java
Locale.setDefault(Locale.<região>)
```
consulte a documentação.