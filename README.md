<!-- markdownlint-disable -->
<p align="center">
    <img src="https://typegraphql.com/img/logo.png" alt="typegraphql"/>
</p>
<!-- markdownlint-enable -->

<!-- markdownlint-disable -->
<h1 align="center">API TypeGraphQL</h1>
<!-- markdownlint-enable -->

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/Batiste2003/tutorial-typegraphql)

## Specs 💼

<!-- markdownlint-disable -->
<ul>
<li>
<a href="https://typegraphql.com" target="_blank" rel="noreferrer">
<img src="https://typegraphql.com/img/logo.png" alt="typegraphql" height="50"/>
</a>
</li>
<li>
<a href="https://typeorm.io" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/typeorm/typeorm/master/resources/logo_big.png" alt="typeorm" height="50"/>
</a>
</li>
<li>
<a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
<img src="https://www.postgresql.org/media/img/about/press/elephant.png" alt="postgresql" height="50"/>
</a>
</li>
<li>
<a href="https://redis.io" target="_blank" rel="noreferrer">
<img src="https://cdn4.iconfinder.com/data/icons/redis-2/1451/Untitled-2-512.png" alt="redis" height="50"/>
</a>
</li>
<li>
<a href="https://nodemailer.com/about/" target="_blank" rel="noreferrer">
<img src="https://nodemailer.com/nm_logo_200x136.png" alt="nodemailer" height="50"/>
</a>
</li>
<li>
<a href="https://www.typescriptlang.org" target="_blank" rel="noreferrer">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968381.png" alt="typescript" height="50"/>
</a>
</li>
<li>
<a href="https://expressjs.com/fr/" target="_blank" rel="noreferrer">
<img src="https://www.pngfind.com/pngs/m/136-1363736_express-js-icon-png-transparent-png.png" alt="express.js" height="50">
</a>
</li>
</ul>
<!-- markdownlint-enable -->

## Requirements ⚠️

You need :

- Node.JS
- Redis
- Git

## Installation ⚙️

Start by cloning the repository :

```sh
git clone git@github.com:Batiste2003/tutorial-typegraphql.git
```

Install all necessary dependencies :

```sh
npm install
```

Edit the ormconfig.json file to connect to your own PostgreSQL database :

```json
{
  "name": "default",
  "type": "postgres",
  "host": "localhost",
  "port": 5432,
  "username": "",
  "password": "",
  "database": "",
  "synchronize": true,
  "logging": true,
  "entities": ["src/entity/*.*"]
}
```

Start your Redis server (im on WSL2 Ubuntu)

```sh
sudo service redis-server start
```

Start your application TypeGraphQL :

```sh
npm start
```

Go to http://localhost:4000/graphql to access your GraphQL server.

**Great you can now create your mutations and queries** 🥳🥳
