
# Desafio - Do While 2021

Resolvi desenvolver uma api em NodeJs, que resolve-se a dificuldade ao acesso à educação.
Levando em consideração tudo que foi requisitado no [formulário](https://efficient-sloth-d85.notion.site/Desafio-Node-js-Express-dbe23f591d5147ab8fb368c0844035d0).

## API Reference

#### Get tematic

```http
  GET /api/v1/education/tematic/
```

#### Get all topics

```http
  GET /api/v1/education/topics/
```

#### Get specific topic

```http
  GET /api/v1/education/topics/${id}/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id of topic to fetch |

#### Get all solutions

```http
  GET /api/v1/education/solutions/
```

#### Get specific solution

```http
  GET /api/v1/education/solutions/${id}/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id of solution to fetch |

#### Get all books

```http
  GET /api/v1/education/books/
```

#### Get specific book

```http
  GET /api/v1/education/books/${id}/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id of book to fetch |

## Usage/Examples

```javascript
$.ajax('/api/v1/education/tematic/').done((data) => console.log(data))
```


## Run Locally

Clone the project

```bash
  git clone this project
```

Go to the project directory

```bash
  cd this project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Links que me ajudaram:
A entender e encontrar formas de solucionar o desafio

- [5 principais obstáculos ao acesso a educação](https://noticiasconcursos.com.br/educacao-no-brasil-5-principais-obstaculos-do-sistema-educacional/)
- [Realidade e desafios na educação](https://www.politize.com.br/educacao-brasileira-realidade-e-desafios/)
- [Acesso à educação](https://www.oxfam.org.br/blog/acesso-a-educacao-no-brasil-os-desafios-da-luta-pela-igualdade/)
## Authors

- [CaioDePaula](https://www.github.com/CaioDePaula)

