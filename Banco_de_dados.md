BANCO DE DADOS

Tipos de dados

- Campos numéricos: inteiro, real
- Campos de texto: nomes...
- Campos de data: ano, mês...
- Booleano: false ou true

Modelagem de entidades

Uma representação de qualquer elemento usada para qualquer fim
exemplo: Uma tabela de camiseta pode ser uma entidade. Uma camiseta tem características de cor, tamanho, formato...

Modelagem de relacionamento

Os relacionamentos de dados entre tabelas podem ser representados de três tipos:

- 1 1 (um para um): Usado quando duas tabelas estão ligadas por uma chave primária. Nesse caso o registro de uma dessas tabelas pode ser usado uma única vez em um dos registros da outra tabela. ex: Um aluno tem uma matricula. (Tabela Aluno) - (Tabela Matricula)

- 1 N (um para vários): Tipo de relacionamento que também acontece de forma direta entre duas tabelas sempre que a chave primária do registro de uma determinada tabela é utilizada várias vezes em outra tabela, sendo este, o tipo de relacionamento mais comum entre tabelas de um banco de dados relacional. Ex: Um aluno tem vários livros. (Tabela Aluno) - (Tabela Livros)

- N N (vários para vários): Usado quando uma tabela vários registros de uma tabela são ligados a vários registros de outra tabela. Ex: Professores  tem vários alunos e alunos tem vários professores. (Tabela Professores) - (Tabela Alunos)

Normalização de dados

Normalizar os dados nada mais é do que transformar os dados para um formato comum e padronizado.

- Formas normais: Buscam garantir a qualidade dos dados

Inserindo tabelas no banco

No Postgre é possivel criar uma tabela por meio do comando "CREATE TABLE".

Inserindo dados no banco

Para inserir os dados usando o Postgre é preciso escrever o comando " INSART INTO 'Nome da Tabela' "

Editando e removendo dados

Para atualizar um dado inserido no banco de dados usamos o comando " UPDATE 'Nome da Tabela = valor' e em seguida filtrar pelo id "where 'id_nome da coluna = numero do id do campo que deseja alterar.

- Permissionamento e views

- Índices:

* Ler a documentação do Postgresql


