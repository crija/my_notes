O que é versionamento?

Registro de mudanças em arquivos, que possibilita recuperação ou acesso a verções anteriores.
Possibilita o desenvolvimento de códigos em parceria com outros colaboradores.

O que é git?

Git é um sistema de versionamento de códigos criado em 2005 e seu principal propósito é guardar alterações feitas nos códigos sem eliminar as versões anteriores.

Ignorar arquivos:
- .gitignore

Alguns comandos que possuo conhecimento:

- git status: Mostra os arquivos que ainda não foram enviados para o servidor
- git add: Adicionar os arquivos que deseja enviar para o servidor
- git commit -m: Descrever o(os) arquivos adicionado(os) antes de enviar para o servidor
- git diff: Mostra as alterações realizadas no códigos
- git restore (nome do arquivo): Desfazer as modificações que foram feitas
- git log: Mostra o histórico dos commits
- git init: Inicializa um repositório
- git clone: Clona um repositório já existente

Alterando um repositório:
- github/repositório que desejo clonar/fork
- github/repositório que desejo clonar/copiar link
- terminal linux/```git clone 'link_repositório```
- fazer alteração no código
- ```git add 'arquivo'```
- ```git commit -m 'descrição da alteração```
- ```git pull HEAD```

Resolvendo um conflito

Quando tentamos subir um commit da máquina local para o repositório remoto, pode acontecer um conflito. Esse tipo de problema é muito comum em ambiente de desenvolvimento, onde fazemos versionamentos de códigos usando o git. Saber resolver esse tipo de erro é crucial para não resultar em perdas de trabalho e tempo.

Identificar o problema:

Nesse exemplo abaixo aconteceu um conflito por eu ter feito um commit no repositório remoto e no repositório local, em seguida tentei subir uma alteração para o repositótio remoto sem antes ter atualizado o repositório local.

O que resultou em um conflito
1. alterei repositório remoto;
2. alterei o repositório local;
3. tentei subir a alteração

Para não resultar em um conflito
1. alterar popositório remoto;
2. trazer alteração para repositório local;
3. fazer alteração no repositório local;
4. subir para repositório remoto

![Capturar_vscodium_20240208145337](https://github.com/crija/my_notes/assets/122110292/0b329724-30c8-4e09-9930-1f83bfb13141)

Nessa imagem podemos identificar o erro pelo hash(identificador do commit) dos commits listados, onde o último commit da direita(local) e o último commit da esquerda(servidor) estão com os hashs diferentes.

Resolver o problema:

. git fetch: Atualiza as referências remotas no repositório local, possibilitando a comparação do repositório remoto com o repositório local. Esse comando é muito importante para a identificação do erro.

. git log origin/main: Lista todos os commits do repositório remoto.

. git log main: Lista todos os commits do repositório local.

. git rebase origin/main: Reorganiza o histórico dos commits da branch local com base na branch remota. O git reoganiza os commits do mais velho para o mais novo, trazendo uma sequência de commits mais linear.

. git push: Enviar o commit para o repositírio remoto.

Evitar problema:

Para que problemas como esse não ocorram é impotante que os repositórios estejam sempre alinhados. É recomendado escolher um dos dois repositórios para fazer as alterações, mas quando é necessário utilizar os dois, cetifique-se que o repositório local esteja alinhado com o repositório remoto, para isso você precisa rodar o git pull antes de fazer qualquer alteração na máquina local. É interessante fazer commits pequenos e frequentes para reduzir a complexidade e ser mais fácil de resolver algum problema futuro.

Em caso de trabalho em equipe, é fundamental manter a equipe informada em caso de altereções.




