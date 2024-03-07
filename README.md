<h1 align="center">Workspace Network API</h1>

Project uses [NestJS](https://nestjs.com/) and [Typeorm](https://typeorm.io/).

## Description

NestJS, Auth, TypeORM, MySql, Mailing, Google OAuth20

## Table of Contents

- [Description](#description)
- [Table of Contents](#table-of-contents)
- [Features](#features)
- [Quick run](#quick-run)
- [Links](#links)

## Features

- [x] Database ([typeorm](https://www.npmjs.com/package/typeorm)).
- [x] Config Service ([@nestjs/config](https://www.npmjs.com/package/@nestjs/config)).
- [x] Mailing ([nodemailer](https://www.npmjs.com/package/nodemailer)).
- [x] Sign in and sign up via email.
- [x] Confirm account via email verification.
- [x] Forget password.
- [x] Reset password.
- [x] Refresh token.
- [x] Google OAuth20.
- [x] Swagger.

## Quick run

```bash
git clone https://github.com/zendy199x/Workspace-Server-NestJS
cd Workspace-Server-NestJS
npm install
cp env-example .env
npm run start:dev
```

## Links

- Swagger: <http://localhost:5000/docs>