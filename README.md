# Registro React + API MongoDB

Este é um projeto de página de **registro simples** e **funcional**, desenvolvido com **React** para o **front-end** e uma **API** em **Node.js/Express** conectada a um banco de dados **MongoDB** para o armazenamento dos dados dos usuários. A página permite o **registro** de novos usuários, **enviando as informações** para o **backend**, que as armazena no banco de dados **MongoDB**.

## Funcionalidades

- Formulário de registro com validação de campos, como e-mail e senha.
- Integração com a API para registrar novos usuários no banco de dados MongoDB.
- Armazenamento seguro de dados, permitindo escalabilidade e flexibilidade no gerenciamento dos usuários.

## Tecnologias Utilizadas

- **React**: Framework para construir a interface do usuário (UI).
- **Node.js** + **Express**: Para criar a API que conecta o front-end com o banco de dados.
- **MongoDB**: Banco de dados NoSQL para armazenar as informações dos usuários.
- **Axios**: Biblioteca para fazer requisições HTTP entre o front-end e o back-end.

## Endpoints

A API expõe o seguinte endpoint principais para interagir com o sistema:

- **POST** `/api/auth/register`: Criação de novos usuários (parâmetros: `nome`, `email`, `senha`).
