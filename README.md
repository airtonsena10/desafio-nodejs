![Logo GoStack 14](https://i.imgur.com/UuhPCqe.png)

<h1 align="center">
 Desafio Conceitos do NodeJS
</h1>

<div align="center">
:rocket:
</div>

## Sobre 🤓

Esse repositório é um desafio apresentado em  do bootcamp GoStack modulo "back end com nodejs"  a ideia seria criar uma aplicação usando conceitos básicos do Node.js!

## Funcionamento 🚀💣

 aplicação server para repositórios como próprio Github, onde se permita  *listar*, *criar*, *atualizar*, *deletar* e da *likes* em um determinado repositório.

Temos os métodos:

- **GET**: http://localhost:3333/repositories

    Será responsável por trazer uma lista de repositórios.

- **POST**: http://localhost:3333/repositories

    Essa rota server para criação de um repositório de um repositório e para isso precisamos passar no corpo da requisição algumas informações, segue o exemplo:

    ```json
    {
    	"title": "Desafio 2",
    	"url": "http://github.com/exemplo",
    	"techs":[
    		"NodeJS",
    		"Express"
    	]
    }
    ```

- **PUT**: http://localhost:3333/repositories/:id

    Essa rota server para atualização de um repositório de um repositório, o **:id** deve ser substituído pelo identificador de algum repositório e por fim passamos, no corpo da requisição, as informações que queremos atualizar, segue o exemplo:

    ```json
    {
    	"title": "Desafio 3",
    	"url": "exemplo.com/exemplo",
    	"techs":[
    		"TypeORM",
    		"React Native"
    	]
    }
    ```

- **DELETE**: http://localhost:3333/repositories/:id

    Essa rota server para exclusão de um repositório de um repositório, o **:id** deve ser substituído pelo identificador de algum repositório.

- **POST**: http://localhost:3333/repositories/:id/like

    Com essa rota você pode basicamente dá um like e um determinado repositório, então toda vez que ela é chamada e aumentado o número de likes.

    Para as rotas **POST** e **PUT** o retorno é um objeto, segue exemplo:

    ```json
    {
    	"id": "1a17d8ae-647d-446f-9a84-0561fb9cd28c",
    	"title": "Desafio 4",
    	"url": "http://github.com/desafio",
    	"techs":[
    		"TypeORM",
    		"React Native"
    	],
    	"likes": 1
    }
    ```

    **Observação:** A retorno da rota **GET** é basicamente a mesma estrutura só que um invês de ser um objeto é um array de objetos. 
    ## 📫 Contact
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/airtonsena)](https://www.linkedin.com/in/airtonsena/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-7159c1?style=flat-square&logo=Gmail&logoColor=white&color=red&link=mailto:airtonsena41@gmail.com)](mailto:airtonsena41@gmail.com)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-7159c1?style=flat-square&color=maroon&logo=instagram&logoColor=white&link=https://www.instagram.com/airtonsena10/)](https://www.instagram.com/airtonsena10/)

    
 
