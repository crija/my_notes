Os tipos primitivos de variáveis Java

- byte; (-128 a 127)
- curto;
- char;
- int;
- flot;
- longo;
- bool; (único que não recebe nemenero)
- duplo.

Classes não executáveis

* Criando uma classe: Definimos uma classe Cachorro e os atributos que o cachorro vai ter. 
```java
classe pública Cachorro { 
nome público da corda;
público String cor;
public int altura;
público duplo peso;
public int tamanhoDoRabo;
}
```
* Criando o objeto cachorro: Criamos um cacherro e atributos como características a esse objeto.
```java
import Animais.Cachorro;
Cachorro cachorro1 = novo Cachorro ();
cachorro1.nome = "doguinho"
cachorro1.cor = "preto"
cachorro1.altura = 25;
cachorro1.tamanhoDoRabo = 5;
```
Métodos 

Podemos definir métodos para interagir com o novo cachorador e definir métodos que não são encontrados nem que são obtidos como um exemplo de variação e uma parte da parte.
exemplos :
```java
...
public void comer () {} Definindo um método público, sem retorno e nada nada nada

public void latir () {Toda vez que eu interagir com esse método ele vai fazer au au
System.out.println ("au au");
}
...
cachorro1.latir (); Vai executar uma ação, que não é um caso au au au au
```
Encapsulamento

Encapsular ou meu objeto de uma forma segura, protegido de acessos indesejados
- pegue
- conjunto

Construtores

Facilitar a construção do objeto que desejam criar
Os construtores recebem o mesmo nome da classe cruzada
Todo o objeto tem um advogado ex: novo Cachorro ()
Mas podemos criar um consultor com argumentos definidos na classe ex: Cachorro público (nome da corda, String cor, int altura...)

Modelagem orientada a objetos

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

-como

Herança

Usamos herança para os códigos não ficarem repetidos e para não precisarmos reescrever os mesmos métodos em todas as classes.
Sendo assim, criamos uma classe pai com todos os métodos que quisermos, se precisar criar novas classes com métodos iguais, usamos a herança. Definimos um nome para a nova classe e reunilizamos o código da classe pai para as classes filhas (acrescentando 'extends' na classe pai).
.exemplo

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

. Todas as classes filhas podem herdar os métodos da classe pai, se quiser acrescentar atributos a mais em algumas das classes filhas, acrescenta-se ditetamente nelas, assim como no exemplo da classe 'Cachorro'.

														


























