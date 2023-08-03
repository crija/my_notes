Os tipos primitivos de variáveis Java:
- byte; (-128 a 127)
- short;
- char;
- int;
- flot;
- long;
- bool; (único que não recebe número)
- double.

Classes não executáveis:

* Criando a classe --Definimos a classe Cachorro e os atributos que o cachorro vai ter.  

public class Cachorro {                                   
	public String nome;
	public String cor;
	public int altura;
	public double peso;
	public int tamanhoDoRabo;
}

* Criando o objeto cachorro: --Criamos um cachorro e atribuimos as características a esse objeto.

import Animais.Cachorro;
	Cachorro cachorro1 = new Cachorro();
	cachorro1.nome = "doguinho"
	cachorro1.cor = "preto"
	cachorro1.altura = 25;
	cachorro1.tamanhoDoRabo = 5;

Métodos: 
Podemos definir métodos para interagir com o nosso cachorro, definir métodos que não fazem nada e/ou métodos que recebem uma variável e faça algo a partir dela.
exemplos:
...
public void comer(){}   Definindo um método público, sem retorno e não faz nada

public void latir(){    Toda vez que eu interagir com esse método ele vai fazer au au
	System.out.println("au au");
}
...
cachorro1.latir(); Vai executar uma ação, que no caso é au au

Encapsulamento:
Encapsular o meu objeto de uma forma segura, protegendo de acessos indesejado
- get
- set

Construtores: 
Facilitam a contrução do objeto que desejamos criar
Os construtores recebem o mesmo nome da classe criada
Todo objeto tem um construtor padrão ex: new Cachorro()
Mas podemos criar um construtor com parâmetros contendo os argumentos definidos na classe ex: public Cachorro(String nome, String cor, int altura...)

Modelagem orientada a objetos:

Classe                						  obj.Cachorro
										 nome = Doguinho
Cachorro									 cor = preto
Nome                          cachorro1			 altura = 25cm
Cor                 ----------------------------->     peso = 5.5kg
Altura									 tamanho do rabo = 5cm
Peso
Tamanho do rabo
	
	|					 obj.Cachorro
	|					nome = Doguinho
	|					cor = preto
	|     cachorro2			altura = 25cm
	--------------------->	peso = 5.5kg				
						tamanho do rabo = 5cm


- Criamos uma classe 'Cachorro', criamos a variável de referência 'cachorro1' para o objeto e em seguida definimos mais uma variável de referência 'cachorro2' para o segundo objeto. Por mais que eles tenham as mesmas características, são objetos distintos. São dois cachorros diferentes com as mesmas características.

						  

















