<h1 align="center">GoBarber API</h1>

<p align="center">
  NodeJS RESTfull API
</p>

## :rocket: Tecnologias

This project was developed with the following technologies:

- [Node.js][nodejs]
- [Express]
- [Docker]
- [Sequelize]
- [PostgreSQL][postgre]
- [Redis]
- [MongoDB]
- [Mongoose]
- [Bcrypt.js][bcryptjs]
- [JWT]
- [Multer]
- [Nodemon]
- [Bee-Queue][bee]
- [Nodemailer]
- [Sentry]
- [Git]
- [VS Code][vscode]
- [ESlint][lint]
- [Prettier - Code formatter][prettier]

## :floppy_disk: Setup Database

**PostgreSQL**

```bash
# Install PostgreSQL with Docker

$ docker run --name gobarber-v1 -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

**MongoDB**

```bash
# Install MongoDB with Docker

$ docker run --name mongo-gobarber-v1 -p 27017:27017 -d -t mongo
```

**Redis**

```bash
# Install Redis with Docker

$ docker run --name redis-gobarber-v1 -p 6379:6379 -d -t redis:alpine
```

**Sequelize Example**

```bash
# Example migration
yarn sequelize migration:create --name=create-users
yarn sequelize db:migrate
yarn sequelize db:migrate:undo
yarn sequelize db:migrate:undo:all
```

[nodejs]: https://nodejs.org/en/
[express]: https://www.npmjs.com/package/express
[docker]: https://www.docker.com/
[bcryptjs]: https://www.npmjs.com/package/bcryptjs
[multer]: https://www.npmjs.com/package/multer
[postgre]: https://www.postgresql.org/
[sequelize]: https://sequelize.org/
[mongodb]: https://www.mongodb.com/
[mongoose]: https://mongoosejs.com/
[redis]: https://redis.io/
[bee]: https://github.com/bee-queue/bee-queue
[nodemailer]: https://www.npmjs.com/package/nodemailer
[nodemon]: https://www.npmjs.com/package/nodemon
[sentry]: https://sentry.io/
[jwt]: https://jwt.io/
[vscode]: https://code.visualstudio.com/
[lint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[prettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
[git]: https://git-scm.com/
