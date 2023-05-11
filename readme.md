![](images/CrudAngular.gif)

# Projeto Angular CRUD de Produtos
Este projeto é um CRUD (Create, Read, Update, Delete) básico de produtos utilizando o Angular. É possível listar, adicionar, editar e remover produtos, além de navegar entre os diferentes componentes.

A aplicação também faz uso de uma mini API em Node.js para manipulação dos dados dos produtos.

### Pré-requisitos
Antes de executar este projeto, é necessário ter o Node.js instalado na máquina.

## Passo a passo para executar o projeto

1 - Clone este repositório em sua máquina usando o comando:
  
  git clone https://github.com/seu-usuario/nome-do-projeto.git

2 - Acesse a pasta do projeto:
  
  cd frontend
  
3 - Instale as dependências do projeto:

  npm install

4 - Inicie a API em Node.js:

  cd backend
  npm install
  npm start
  
5 - Em outro terminal, inicie a aplicação Angular: http://localhost:4200

  cd ..
  npm start
  
6 - Acesse a aplicação no seu navegador em 

## Funcionalidades

### Listagem de produtos
A página inicial da aplicação exibe a listagem de todos os produtos cadastrados, exibindo as informações de nome, descrição e preço. É possível navegar para a página de edição ou exclusão de cada produto através dos botões na tabela.

### Adição de produto
Através do botão "Adicionar Produto" na página inicial, é possível acessar o formulário de adição de produtos. É necessário preencher os campos de nome, descrição e preço para adicionar um novo produto. Após a adição, o usuário é redirecionado para a página de listagem.

### Edição de produto
Ao clicar no botão de edição de um produto na página de listagem, o usuário é redirecionado para a página de edição, onde pode alterar os valores de nome, descrição e preço do produto. Após a edição, o usuário é redirecionado para a página de listagem.

### Exclusão de produto
Ao clicar no botão de exclusão de um produto na página de listagem, o usuário é questionado sobre a confirmação da exclusão. Caso confirme, o produto é removido da lista.

## Tecnologias utilizadas

- Angular
- Node.js
- Typescript

## Contribuindo

### Contribuições são sempre bem-vindas! Para contribuir com este projeto, siga os seguintes passos:

1 - Crie um fork deste repositório

2 - Crie uma nova branch com suas modificações:

  git checkout -b minha-modificacao

3 - Faça as suas modificações e faça um commit:

  git commit -am 'Adicionando minha modificação'

4 - Faça um push da sua branch para o seu fork:

  git push origin minha-modificacao
  
 5 - Crie um pull request para este repositório com suas modificações
 
 6 - Aguarde a revisão e merge do seu pull request
 
 ## Licença
 
 Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para mais detalhes.
