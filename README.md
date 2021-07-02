<h1 align="center">  PLACEHUB  </h1>


## 📕 Indice


* [📋 Sobre](##Sobre-o-projeto)
* [🖥 Tecnologias:](#🖥-Tecnologias)
* [🏋️‍♀️ Como rodar o projeto](#🏋️‍♀️-Como-contribuir-para-o-projeto)
* [🦸 Autor](#🦸-Autor)
* [📝 Licença](#📝-Licença)



## 💻 Sobre o projeto


Este projeto foi desenvolvido para vaga de Desenvolvedor Fullstack Junior na Placehub


## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:
- [Express]
- [Typescript]
- [MongoDB]
- [Multer]

## Features

1. Adicionar uma pessoa
2. Remover pessoa
3. Upload de imagem
4. Procurar pessoa
5. Atualizar pessoa
6. Paginação


## 🏋️‍♀️ Como Rodar o projeto

1. Faça o git clone do projeto.
2. Entre na pasta do projeto e escreva os seguintes comandos `yarn` e `yarn dev`
3. Para testar a api use o programa de sua preferência (Isominia, Postman ....)

## 🏋️‍♀️ Rotas

1. get('/persons')
    - Para usar a paginação adicione a query 'page'
2. get('/search')
    - Para procurar use a query 'name'
3. post('/persons')
    - Ultlize Multipart Form para adicionar uma imagem {name, email, file}
4. patch('/persons/:id')
    - Ultlize Multipart Form para atualizar uma imagem {name, email, file}
5. delete('/persons/:id')
    - Deleta uma pessoa a partir do id

## 🦸 Autor

 <img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/62263143?s=460&u=2d740bbcbd193e223e104d59cca9a1b0b8831152&v=4" width="100px;" alt=""/>

<p>WESLEY SOUSA</p> 

</p>

<hr>

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito por Wesley Sousa 👋🏻 [Entre em contato!](https://api.whatsapp.com/send?phone=5598985595646&text=Informe%20seu%20nome%20%C3%A9%20qual%20o%20assunto.!)