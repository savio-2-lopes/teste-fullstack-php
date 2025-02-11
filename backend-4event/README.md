# Teste Fullstack PHP - Backend

![GitHub repo size](https://img.shields.io/github/repo-size/savio-2-lopes/personal-portfolio)
![GitHub language count](https://img.shields.io/github/languages/count/savio-2-lopes/personal-portfolio)
![GitHub top language](https://img.shields.io/github/languages/top/savio-2-lopes/personal-portfolio)
![GitHub followers](https://img.shields.io/github/followers/savio-2-lopes?label=Follow&style=social)

<br>

<p align="center">
  <img src="./.github/gif.gif" width="100%" alt="Web">
</p>

<br>

## Tópicos

[Tecnologias](#tecnologias)

[Agradecimentos](#agradecimentos)

## Observação

Necessário possuir Docker instalado na máquina para rodar Backend e Frontend. Caso tenha mysql rodando na máquina, recomendo desativa para evitar conflitos de portas.

<br>

## Tecnologias do Backend

Tecnologias e ferramentas utilizadas no desenvolvimento da Web:

- [PHP 8.1.0](https://www.php.net/releases/8.1/en.php)
- [Docker](https://www.docker.com/)
- [Swooler](https://openswoole.com/)
- [MySQL](https://www.mysql.com/)

<br>


### API endpoints

`GET /veiculos`

Retorna todos os veículos

---

`GET /veiculos/:id`

Retorna os veículos de acordo com o termo passado parâmetro `q`

---

`PUT /veiculos/:id`

Retorna dado de um veículo com base no `id`

---
`POST /veiculos`

Adiciona um novo veículo

<br>

## Instalação Backend

```bash
# Rodando o servidor com docker
$ docker compose up --build

# Necessário criar o banco de dados 4Events.
# Para isso, na pasta app/ há o script sql create-table.
# Para acessar o banco de dados do Docker, as credenciais são as seguintes:
$ user: root;
$ password: root;
$ db: 4Events-backend;

## A api estará rodando usando IP da máquina
$ http:<SEU_IP>:8000

```

<br>

## Autor

[![Github Badge](https://img.shields.io/badge/-Github-373737?style=flat&logo=Github&logoColor=white)](https://github.com/savio-2-lopes)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-8a3ab9?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/savioaugulopes/)
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/savio-lopes/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=flat&logo=gmail&logoColor=white)](mailto:savio.dev.lopes@gmail.com)

Feito com ❤️ por [Savio Lopes](https://www.linkedin.com/in/savio-lopes/)

---


## 💙 Agradecimentos

Gostaria de expressar meus sinceros agradecimentos à [4Events](https://github.com/4events) pela oportunidade de participar deste desafio. Se você encontrar algum problema ao executar os projetos ou tiver alguma dúvida, sinta-se à vontade para entrar em contato comigo. Estou aqui para ajudar e ficarei feliz em auxiliá-lo no que for necessário.
