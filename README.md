# Desafio 2 - Curso GoStack Rocketseat

```Seguindo o template proposto, criar as seguintes rotas:```
- POST /repositories: A rota deve receber title, url e techs dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: { id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.
- GET /repositories: Rota que lista todos os repositórios;
- PUT /repositories/:id: A rota deve alterar apenas o title, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota;
- DELETE /repositories/:id: A rota deve deletar o repositório com o id presente nos parâmetros da rota;
- POST /repositories/:id/like: A rota deve aumentar o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

##### Executar **_yarn test_** para avaliar as diretrizes passadas.

### Instalação Local
- git clone https://github.com/diegoMasin/desafio-2-curso-rocketseat.git
- execute no terminal dentro da pasta do projeto: **yarn**
Obs: Instale o yarn no seu sistema operacional.
- para rodar o projeto execute no terminal: **yarn dev**
Obs: endereço base da api: **http://localhost:3333**
