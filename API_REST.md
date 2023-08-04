O que são APIs HTTP e APIs HTTP REST?

- API é a interface
- HTTP é o protocólo
- REST é o padrão que usamos para definos os endpoints

Componentes da Comunicação HTTP

- URL é o localizador de um recurso
- URI é o dentificador
- Método(method) indica uma ação que deve ser executada no computador
- Corpo(body):
- Cabeçalho(header) nos ajudam a controlar acessos, quais são os dados que eu vou aceitar no retorno, controle de sessão

Arquitetura de uma API

- A API é uma interface que fica do lado do servidor. 
- Recebe os dados, pedidos, informação e devolver o mínimo de exposição das regras internas. Se deu tudo certo ou aconteceu algum erro e qual erro.
- Uma API tem que se comportar de forma competente, contectando os usúarios e a regra de negócio.
- Para uma arquitetura de API funcior bem precisamos saber quais recuros nós vamos usar, quais dados eu vou entregar e em qual formato, como a segurança vai ser implementada, quanto tempo demora para o retorno dos dados
- É importante fazer a arquitetura de uma API antes de fazer o códigos para não ocorrer problemas como falta de segurança, falta de eficiência...
- Ter uma estrutura de rotas, onde vamos encontrar os dados, cadastrar...

O que é REST?

- É um estilo de arquitetura de API, um conjunto de ideias vão definir como um recurso vai ser acessado na rede
- Da ao desenvolvedor a posibilidade de pensar apenas na implementação sem precisar pensar na interface.

Métodos de acesso e Método GET

- GET é para obter os dados de uma API. Requisição e Resposta
- POST é usado para postar dados
- PUT / PATCH é usado para atualizar dados
- DELETE usado para apagar um dado

Alterando dados com métodos POST, PUT e DELETE

- GET é usado para buscar algo 
- POST é usado para criar algo
- PUT é usado para enviar dados no intuíto de atualizar algo por completo
- PATCH é usado para atualizar parte de algo
- DELETE é usado para deletar algo
  
Obs: Os únicos métodos que não tem corpo são: GET e DELETE.

Status Code, Altenticação e Cookies
Status Code: Mensagens de erros ou ok direcionadas para o usuário. Os Status Code estão organizados em classe.
Os Status Code são 3 números, a classe é sempre o primeiro número.
- 2xx - Código de sucesso
- 3xx - Redirecionamento
- 4xx - Erros de cliente
- 5xx - Erros de servidor












