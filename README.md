## API Restful com Node.js, Express, Typescript, TypeORM, Postgres, Redis, Docker, etc

Aplicação backend para gestão de vendas com funcionalidades para criação de cadastro de produtos, cadastro de clientes, pedidos de compras e uma completa gestão de usuários da aplicação, com autenticação via Token JWT, recuperação de senha por email, atualização de perfil, atualização de avatar, e muito mais.

Através do TypeORM implementei Entidades e Repositórios para cada recurso a ser consumido na API.

Acesse a [página do curso na Udemy](https://www.udemy.com/course/api-restful-de-vendas/) para conferir o conteúdo.

## Objetivo

Planejado de forma a escalar e evoluir de acordo com as novas versões das ferramentas aqui utilizadas.

A ideia é ao longo do tempo incluir novas funcionalidades, simular alterações de ferramentas em uso, como por exemplo alterar o SGDB de Postgres para MySql, mantendo uma dinâmica de evolução constante do projeto.

## Rodando a aplicação no seu PC

Faça um clone deste repositório e instale no seu ambiente de desenvolvimento usando o seguinte comando no seu terminal (escolha um diretório apropriado):

```
git clone https://github.com/joannaneves/api-vendas.git
```

Após clonar o conteúdo do repositório, acesse o diretório criado e efetue a instalação das dependências:

```
cd api-vendas

yarn

# ou

npm install
```

Após essa instalação execute a aplicação com o comando `yarn dev` ou `npm run dev`. O servidor estará em execução no endereço `http://localhost:3333`.
