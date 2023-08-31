## Python
A linguagem de programação Python foi criada em 1991 como sucessora da linguagem ABC. ABC era uma linguagem de programação com muitas limitaçõs e a ideia do criador de Python era criar uma linguagem com scripts fáceis.

Python é uma linguagem interpretada, isso quer dizer que o código criado em python é executado pelo operador ou interpretador.

### Conteúdo base da linguagem

#### Identação: A linguagem Python possui identação padronizada.

ex:
``` python
print("Hello, World!")
  print("My name's Carla")
```

#### Funções: A declaração de uma função é dividida em três partes: nome, parâmetro e corpo.

ex:
``` python
def somar(a=0, b=0, c=0):
    s = a + b + c
    return s

r1 = somar(4, 8, 9)
r2 = somar(3, 9) 
r3 = somar(1, 4)

print(f'Os resultados foram {r1}, {r2}, {r3}')
- Retornará todos os valores dentro do format.
```

#### Tipos de dados: string,inteiro, float, booleano.
ex:
``` python
nome = str(input('Digite seu nome: ')) #Tipo str recebe um texto. Tudo que está entre aspas símples ou aspas dúplas no python é uma str.

idade = int(input('Digite sua idade: ')) #Tipo int recebe um número inteiro.

altura = float(input('Digite sua altura: ')) #Tipo float recebe um número fluante.

while True: # Tipo bool é False ou True. É bastante usado para parar ou continuar um loop.
  resposta = str(input('Deseja salvar seus dados? '))
  if resposta == não:
    break
```

Estrutura Condicional: if, elif, else.
ex:
``` python
nome = str(input('Seu nome é Guilherme? '))
if nome == 'sim': # Primeira condição 
  print('Nome salvo com sucesso!')
elif nome == '': # Segunda condição. O elif pode ser usado quantas vezes for necessário.
  print('Ocorreu um erro!')
else: # Ultima condição.
  print('É necessário preencher seu nome novamente.')
```

#### Lista de valores: listas [], dicionário {}, tupla ().
``` python
list = ['Carla', 18, 'brasileira', 'estudante'] # Uma lista pode ser consultada pela posição dos elementos, podendo acrescentar ou remover elementos.
dict = {'nome': 'Carla', 'idade': 18} # O dicionário pode ser consultado pela chave, assim como a lista o dicionario também é mutável.
tupla = (1, 45, 23, 56) # Ao contrário da lista e do dicionário as tuplas são IMUTÁVEIS.
```

### Variável
Uma variável guarda um tipo de dado.
ex:
```python
carro = 'Veloster' # carro é a variável que está guardando um dado do tipo str.
print(carro) # Comando para mostrar o que tem guardado na variável.
```

### Comparações usadas na linguagem
ex:
``` python
a = 5
b = 15
c = 20

print(a == b and b > c)
print(a < b or b > c)
print(not a == b)

```
