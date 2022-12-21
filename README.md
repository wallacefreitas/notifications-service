<h1 align="left">
    <a href="https://pt-br.reactjs.org/">🔗 Notifications Service - Ignite Lab</a> 
</h1>

<img src="https://img.shields.io/badge/license-MIT-green">

<p align="left" style="margin-top:5px">🚀 API development using NodeJS with the NestJS framework, the Prisma ORM, along with Domain Driven Design (DDD) concepts at IgniteLab (Rocketseat)</p>

# Running

#### 🧭 Running in a server

```bash

# Clone this repository
$ git clone git@github.com:wallacefreitas/notifications-service.git

# Access the folder project in your terminal/cmd
$ cd notifications-service

# Create a file .env and add a variable:
VITE_API_URL=http://localhost:3000/

# Install the dependencies
$ npm i

# Execute Prisma Generate
npx prisma generate

# Run  the application in development mode
$ npm run start:dev

# The application will open in port:3000 - go to http://127.0.0.1:3000/

# Run  the application in test mode
$ npm run test:watch

```

---

## 🛠 Technologies

The following tools were used in building the project:

> See the file [package.json](package.json)

#### **Server**

- **[Prisma](https://www.prisma.io/)**
- **[SQLite](https://www.sqlite.org/index.html)**
- **[NestJS](https://nestjs.com/)**
- **[JestJS](https://jestjs.io/pt-BR/)**

> See the file [package.json](package.json)

---

## 📝 License

This project is under license [MIT](LICENSE.md).

Made by Wallace de Freitas 👋🏽
