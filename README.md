# luckyDraw
Projeto para gerenciar sorteios


## Stack utilizada

**Back-end:** NodeJs, typescript

**Database** Postgres

**Docker** Dockerfile, docker-compose

## Requisitos

- NodeJs
- Typescript
- Certifique-se de ter o Docker e o Docker Compose instalados na sua máquina. Você pode baixá-los em [Docker](https://www.docker.com/get-started). (Opcional)

## Instalação

1. Clone este repositório para o seu ambiente de desenvolvimento.

```shell
git clone https://github.com/Luansantosdevpy/LuckyDraw.git
```

2. Navegue até o diretório do projeto.
```shell
cd LuckyDraw
```
3. Copie o env.sample para o env
```shell
  cp env.sample .env
```

4. Modifique as variáveis do seu .env

5. Inicie o aplicativo.
```shell
yarn dev
```

## Via Docker

1. Crie um arquivo .env na raiz do projeto para configurar as variáveis de ambiente necessárias, como no env.sample.
```shell
cp .env.sample .env
```

2. Modifique as variáveis do seu .env

3. Inicie os contêineres:
```shell
docker-compose up
```
Isso iniciará o aplicativo e o banco de dados PostgreSQL em contêineres separados.

Divirta-se.


## Variáveis de Ambiente

Para rodar esse projeto, você vai precisar adicionar as seguintes variáveis de ambiente no seu .env
Esteja a vontade para criar os valores de acordo com o que preferir

`DB_POSTGRES_USER`

`DB_POSTGRES_PASSWORD`

`DB_POSTGRES_HOST`

`DB_POSTGRES_PORT`

`DB_POSTGRES_NAME`

`DATABASE_URL=postgresql://user:password@host/name`

## Autores

- [@luansantosdevpy](https://www.github.com/luansantosdevpy)


## Licença

[MIT](https://choosealicense.com/licenses/mit/)
