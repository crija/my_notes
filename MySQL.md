## Anotações baseadas no curso de MySQL do Curso Em Vídeo
Os bancos de dados são construídos da seguinte forma:
- Banco de dados
- Tabelas
- Registros
- Campos
### Criando um bando de dados:
Começamos criando o banco de dados no MySQL Workbench
```java
create database 'nome do banco'
```
Em seguida criamos uma tabela dentro do banco de dados
``` java
create table 'nome da tabela'
```
Agora vamos criar os registros que vão ficar dentro da tabela e em seguida adicionar os tipos de cada campo

``` java
use cadastro;
create table pessoas (
    nome varchar(30),
    idade tinyint(3),
    sexo char(1),
    peso float,
    altura float,
    nacionalidade varchar(20)
);
```
- Obs: O símbolo de ' ; ' determina o fim do comando.

Para ver como funciona a estrutura interna da tabela basta adicionar a baixo da tabela o comando
``` java
describe 'nome da tabela'
```
Se preferir rodar direto no terminal, escreva os seguintes comandos:

Para saber quais bancos de dados foram criados
```
show detabase;
```
Para entrar em um bando de dados criado
```
use 'nome do banco';
```
Para saber qual banco de dados está aberto
```
status;
```
Para visualizar as tabelas do banco de dados
```
show tables;
```
Para visualizar as colunas da tabela acessada
```
describe 'nome da tabela'
```
Sair do MySQL
```
ext
```







