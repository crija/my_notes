# Programação Orientada a Objeto com Java

### Tipos primitivos de variáveis Java

- byte; (-128 a 127)
- curto;
- char;
- int;
- flot;
- longo;
- bool; (único que não recebe nemenero)
- duplo.

### Classes não executáveis

* Criando uma classe: Definimos uma classe com o nome Cachorro e os atributos. 
```java
classe pública Cachorro { 
nome público da corda;
público String cor;
public int altura;
público duplo peso;
public int tamanhoDoRabo;
}
```
* Criando o objeto cachorro e definindo suas características.
```java

import Animais.Cachorro;
Cachorro cachorro1 = new Cachorro ();
cachorro1.nome = "doguinho"
cachorro1.cor = "preto"
cachorro1.altura = 25;
cachorro1.tamanhoDoRabo = 5;
```

### Métodos 

Os métodos definem o comportamento dos objetos de uma classe
- Vamos criar o método comer que não fará nada e em seguida vamos criar o método latir e sempre que interagirmos com esse método ele vai fazer algo.

```java
...
public void comer () {} 

public void latir () {Toda vez que eu interagir com esse método ele vai fazer au au
System.out.println ("au au");
}
...
cachorro1.latir (); Vai executar uma ação, que não é um caso au au
```

### Atributos

Os atributos definem a estrutura de uma classe

### Encapsulamento

Encapsular o meu objeto de uma forma segura, protegido de acessos indesejados
- Podemos e devemos definir quem terá acesso aquela informação

```java
_________________________________________________________________________________________
   Visibilidade                                | public | protected | default | private |
A partir da mesma classe                       |    v	|     v	    |	 v    |	   v	|
Qualquer classe no mesmo pacote                |    v	|     v     |	 v    |	   x	|
Qualquer classe filha no mesmo pacote          |    v	|     v     |	 v    |	   x	|
Qualquer classe filha em pacotes diferentes    |    v	|     v     |	 x    |	   x	|
Qualquer classe em pacote diferente            |    v	|     x     |	 x    |	   x	|
_________________________________________________________________________________________

```

#### Construtores

Facilitar a construção do objeto que desejam criar
Os construtores recebem o mesmo nome da classe cruzada
Todo o objeto tem um advogado ex: novo Cachorro ()
Mas podemos criar um consultor com argumentos definidos na classe ex: Cachorro público (nome da corda, String cor, int altura...)

### Modelagem orientada a objetos

```
Classe obj.Cachorro
nome = Doguinho
Cachorro cor = preto
Nome cachorro1 altura = 25cm
Cor                 ----------------------------->              peso = 5.5kg
Altura tamanho do rabo = 5cm
Peso
Tamanho do rabo
	
| obj.Cachorro
| nome = Doguinho
| cor = preto
| cachorro2 altura = 25cm 
	------------------------>	        peso = 5.5kg				
tamanho do rabo = 5cm
```

### Herança

Usamos herança para os códigos não ficarem repetidos e para não precisarmos reescrever os mesmos atributos em todas as classes.
Sendo assim, criamos uma classe pai com todos os atributos que quisermos. Na criação de uma classe filha ela herdará todos os atributos da classe pai.

						Classe Pai

						Animal
						Nome
						Cor 
						Altura
						Peso

						  ^
						  |
						  |
						  |
		^				  |                           ^
		|					                      |
	Classe Filha	  		      Classe Filha		Classe Filha
	
	Cachorro				Passaro           	    Gato
	Tamanho do rabo			

- Se for necessário acrescentar um atributo em uma classe específica, acrescenta - se 

					
Polimorfismo

É a reescrita de um método herdado de uma classe, sem utilizar nenhum comportamento da classe pai pra esse método






























														


























