# Rosemary

### Cooking is a love you can taste.

Rosemary is a web app where users can read a follow other user created recipes and post their own.

<p align="center">
  <img src="./assets/Rosemarin.png" />
</p>

## Developed with...

<a href="https://reactjs.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" /></a>
<a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/typescript-colored.svg" width="36" height="36" alt="TypeScript" /></a>
<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" /></a>
<a  href="https://expressjs.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/express-colored.svg" width="36" height="36" alt="Express" /></a>
<a  href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" /></a>

-   **React Native** - Front end library for building Web user interfaces.
-   **TypeScript** - Strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.
-   **Express.JS** - Fast, unopinionated, minimalist web framework
-   **PostgresSQL** - Powerful, open source object-relational database system
-   Passion for software development and user interaction

## Getting started

1. Clone the repo

```
git clone https://github.com/RomelClavel/rosemarin.git
cd rosemarin
```

1. Install dependencies

```

npm install //In both client and server

```

<sub><sup>May have to force the install because of a dependency clash</sup></sub>

2. Change your credentials on server/models/index.js & .env files

```
const sequelize = new Sequelize('postgres', 'postgres', process.env.PASSWORD_DB, {
	host: 'localhost',
	port: 5432,
	dialect: 'postgres',
});
```

5. Start development server

```
FRONT-END => npm  start
BACK-END => npm run dev
```

## What can Rosemay do?

-   ### Create your own account to use on the app
-   ### See and Follow recipes from users around the world
-   ### Create you oen recipes
-   ### Add ingredients to your shopping straight from the recipes
