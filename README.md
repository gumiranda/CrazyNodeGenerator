# CrazyNodeGenerator

Conheça esse poderoso template gerador de CRUD dinâmico do Dev Doido. Nele você será capaz de gerar todos os arquivos necessários para implementar numa API REST um CRUD pra qualquer domínio de negócio usando MongoDb e Fastify. O gerador de arquivo produz testes unitários, testes automatizados, rotas, controllers, useCases e repositories de forma limpa e dinâmica através de factories e dependency injection.

Tudo referente a autenticação já está implementado usando jsonwebtoken para geração de access token e refresh token nas pastas user e account. Como diferencial temos um endpoint exclusivo de lista paginada de usuários próximos usando geospatial queries do MongoDb.

Para personalizar a geração de arquivo basta modificar os arquivos modelo existentes na pasta generators.

# Setup do projeto

- git clone na url do projeto
- cd /CrazyNodeGenerator
- colocar variáveis de ambientes no .env seguindo o exemplo de .env-example
- `npm install` ou `yarn`
- `npm run build` ou `yarn build`
- `npm run start` ou `yarn start`
- FEITO! 🚀

# Rodando testes no Jest

- `yarn test:all` ou `npm run test:all`
- FEITO! 🚀

# Gerando CRUD dinamicamente

- `yarn generate`
- responda via CLI qual tipo de geração de arquivo deseja, caso seja todas basta digitar `all`
- coloque via CLI qual o nome do domínio de negócio a ser gerado. Ex: 'categoria'.
- FEITO! 🚀
