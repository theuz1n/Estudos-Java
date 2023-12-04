para se fazer uma entrada de dados você irá criar um objeto do tipo "Scanner".

**OBS:** faça o sc.close para fechar o objeto Scanner

ex:
``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
	}
	
}

```
  

**ler string**
``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
		string a;
		a  = sc.next();
		sc.close()
	}
	
}

```

**ler int**

``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
		int a;
		a  = sc.nextint();
		sc.close();
	}
	
}

```

**ler Double**

``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
		Double a;
		a = sc.nextDouble();
		sc.close()
	}
	
}

```

**ler char**

``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
		char a;
		a = sc.nextcharAT(0);
		sc.close()
	}
	
}

```


### Problema da Quebra de linha pendente

Problema: Quando você usa um comando de leitura diferente do `nextLine( )`e dá alguma quebra de linha, essa quebra de linha fica **"pendente"** na entrada padrão.

ex:

``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
		int x ; string s1,s2;
		
		x = sc.nextInt();
		s1 = sc.nextLine();
		s2 = sc.nextLine();
		
		sc.close()
	}
	
}

```

Ao realizar a leitura da entrada dos dados ficará uma linha pendente assim não lendo a entrada da variável s2.

**Solução:** Se você então fizer um `nextLine()`, aquela quebra de linha pendente será absorvida pelo `nextLine()`.

Ex: 

``` java
public class main(){
	public Static void main(Strng[] args){
		Scanner sc = new Scanner(system.in);
		int x ; string s1,s2;
		
		x = sc.nextInt();
		sc.nextLine();
		s1 = sc.nextLine();
		s2 = sc.nextLine();
		
		sc.close()
	}
	
}

```
