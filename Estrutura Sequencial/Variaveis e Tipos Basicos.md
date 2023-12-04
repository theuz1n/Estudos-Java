
variáveis e tipos básicos em Java

Variável: é uma porção de memoria(RAM) utilizada para armazenar dados durante a execução dos programas.

#### Declaração de Variáveis

Sintaxe:
```
<tipo> <nome> = <valor inicial> ;
```
exemplos:
```java
int idade = 10

double peso = 68.6
```  

Uma variável possui:
- nome
- tipo
- valor   
- endereço
##### Tipos primitivos em Java

![tipos primitivos](https://hermes.dio.me/articles/cover/9d24e608-c930-4770-8518-7c2aace1a640.png)

tipos numéricos inteiros:

- byte
- short
- int
- long

tipos numéricos com pontos flutuantes:
- float
- double

um carácter Unicode:
- char

valor verdade:
- boolean

cadeia de caracter:
- string

#### Dicas de Como Nomear Variáveis

1. não pode começar com dígito: use uma letra ou _
2. não pode ter espaço em branco
3.  não usar acentos ou til
4. sugestão: use o padrão " camel case" (O padrão consiste em sempre que a variável tiver um nome composto com mais de uma palavra você coloca uma letra maiúscula. Ex: salarioDoFuncionario