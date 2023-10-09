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

Assuntos para pesquisar e entender:

- Relacionar classes usando o id

- Normalização de dados

- Formas normais: Buscam garantir a qualidade dos dados

- Inserindo tabelas no banco

- Inserindo dados no banco

- Editando e removendo dados

- Permissionamento e views

- Índices:

* Ler a documentação do Postgresql


