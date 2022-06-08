![WATTIO](http://wattio.com.br/web/image/1204-212f47c3/Logo%20Wattio.png)

### Como Fazer Funcionar a Solução:
- Clone o repositório para uma pasta de Sua preferencia utilizando por exemplo:
  $ git clone git@github.com:RickCruzz/backend.git

- Acesse a pasta com os dados do repositório e monte uma imagem docker a partir do repositório
 $ docker build -t desafio .

- Após criar a imagem você pode verificar através do comando: 
  $ docker image ls
- Basta inicializar a imagem se tudo deu certo com o comando:
$ docker run --name desafio -p 80:80 desafio

- Se os logs começaram a aparecer basta acessar a página de documentação através do seu navegador de preferência:
https:localhost:80/docs

### MUITO OBRIGADO PELO TESTE! Foi Incrível e desafiador :)


#### Descrição

O desafio consiste em implementar um CRUD de filmes, utilizando [python](https://www.python.org/ "python") integrando com uma API REST e uma possível persistência de dados.

Rotas da API:

 - `/filmes` - [GET] deve retornar todos os filmes cadastrados.
 - `/filmes` - [POST] deve cadastrar um novo filme.
 - `/filmes/{id}` -  [GET] deve retornar o filme com ID especificado.

O Objetivo é te desafiar e reconhecer seu esforço para aprender e se adaptar. Qualquer código enviado, ficaremos muito felizes e avaliaremos com toda atenção!

#### Sugestão de Ferramentas 
Não é obrigatório utilizar todas as as tecnologias sugeridas, mas será um diferencial =]

- Orientação a objetos (utilizar objetos, classes para manipular os filmes)
- [FastAPI](https://fastapi.tiangolo.com/) (API com documentação auto gerada)
- [Docker](https://www.docker.com/) / [Docker-compose](https://docs.docker.com/compose/install/) (Aplicação deverá ficar em um container docker, e o start deverá seer com o comando ``` docker-compose up ```
- Integração com banco de dados (persistir as informações em json (iniciante) /[SqLite](https://www.sqlite.org/index.html) / [SQLAlchemy](https://fastapi.tiangolo.com/tutorial/sql-databases/#sql-relational-databases) / outros DB)


#### Como começar?

- Fork do repositório
- Criar branch com seu nome ``` git checkout -b feature/ana ```
- Faça os commits de suas alterações ``` git commit -m "[ADD] Funcionalidade" ```
- Envie a branch para seu repositório ``` git push origin feature/ana ```
- Navegue até o [Github](https://github.com/), crie seu Pull Request apontando para a branch **```main```**
- Atualize o README.md descrevendo como subir sua aplicação

#### Dúvidas?

Qualquer dúvida / sugestão / melhoria / orientação adicional só enviar email para hendrix@wattio.com.br

Salve!
