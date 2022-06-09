# Api-RESTfull-Node
Um desafio backend, onde usei o framework do express, com o banco de dados do MongoDb

## Empresa Field Control
### "challenge": "Backend Developer 1" 
Desenvolver uma API JSON RESTful expondo operações de um CRUD.

Pense em algum recurso (use sua criatividade), pode ser gatos, personagens dos senhores do anéis, personagens da marvel, pokemon, enfim, o que você quiser..

Utilize todos os métodos (GET, POST, PUT, PATCH, DELETE)

Você terá que expor os seguintes endpoints para o recurso escolhido:

Método	URL	Comportamento esperado
- GET	/resources	Recupera a lista dos recursos, essa ação deve ser paginada e deve possibilitar busca pelas propriedades do recurso
- GET	/resources/:id	Recupera um recursos em especifico pelo id
- POST	/resources	Insere um novo recurso
- PUT	/resources/:id	Altera um recurso existente
- PATCH	/resources/:id	Altera parcialmente um recurso existente
- DELETE	/resources/:id	Exclui um recurso existente <br>
Qual Web Framework? pode ser Express.js, Hapi, Restify, Koa, fastify, o que você preferir :P<br>
Qual Banco de dados? Mesmo pensamento, pode ser MongoDb, DynamoDb, Postgres, MySql.. enfim, não importa :)<br>
**Atenção:** Você deve se preocupar com sanitização, validação e semântica.

-------------------------------------------------------------------------------------------------------------------------------------------------
## Respostas
- Usei as ferramentas do express, MongoDb e Postman.
- Estas ferramentas foram fáceis de usar, o Express e postman deixou a manutenção das rotas muito fácil de testar e construir. Utilizei express pelo fato dele ser bem popular, visto que eu não conhecia as ferramentas pra desenvolver um API.
- O grande desáfio de fazer esta API foi sair da minha zona de conforto e conhecimentos básicos e botar a mão na massa. Mas foi uma experiência que no final das contas se mostrou fácil e de grande aproveitamento.
- Eu acho que eu poderia colocar mais segurança nesta API e talvez fazer ela mais complicada, como buscar e colocar pokemons e seus tipos em um banco de dados.
