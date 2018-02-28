# Teste Apponte - Backend Pleno
Desenvolver uma pequena API utilizando Node.js

## Instruções
- Siga as especificações abaixo.
- Crie um README com as instruções para compilar e rodar o projeto.
- O link do projeto deverá ser enviado ao término do prazo.

## Especificações tecnicas
- Criar uma rota onde podemos cadastrar um usuário com os campos: nome, email, senha, endereço, estado, cidade e descrição
- Criar uma autenticação utilizando JWT e Koa ou Express para as rotas
- Criar uma rota onde o acesso aos dados só será permitido para usuários autenticados
- Utilizar MongoDB para armazenar os dados
- Testes automatizados é um diferencial

## Especificações funcionais
### Autenticação
Deverá ser criada uma rota para autenticação de usuários com email e senha.
Ao realizar a autenticação a aplicação deve retornar um token.

### Rota protegida
Também deverá ter uma rota que só irá retornar os dados para usuários autenticados.
Os dados a serem retornados devem ser o perfil completo do usuário logado.

## O que será avaliado?
- Organização do projeto
- Lógica do código
