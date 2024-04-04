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
- Para uma arquitetura de API funcior bem precisamos saber quais recuros nós vamos usar, quais dados eu vou entregar e em qual formato, como a segurança vai ser implementada, quanto tempo demora para o retorno dos dados.
- É importante fazer a arquitetura de uma API antes de fazer o códigos para não ocorrer problemas como falta de segurança, falta de eficiência...

O que é REST?

- É um estilo de arquitetura de API, um conjunto de ideias vão definir como um recurso vai ser acessado na rede
- Da ao desenvolvedor a posibilidade de pensar apenas na implementação sem precisar pensar na interface.

Formas de se comunicar com uma API. Usa-se a bibliotéca request para acessar

- GET: Buscar informações em uma API
- POST: Criar informações
- PATCH: É usado para atualizar parte de algo
- PUT: Usado para enviar dados no intuíto de atualizar algo por completo
- DELETE: Excluir informação

Obs: Os únicos métodos que não tem corpo são: GET e DELETE.

Status Code, Altenticação e Cookies
Status Code: Mensagens de erros ou ok direcionadas para o usuário. Os Status Code estão organizados em classe.
Os Status Code são 3 números, a classe é sempre o primeiro número.
- 2xx - Código de sucesso
- 3xx - Redirecionamento
- 4xx - Erros de cliente
- 5xx - Erros de servidor












