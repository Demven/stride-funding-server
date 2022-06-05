# stride-funding-server

The back-end part of the "Stride Funding" demo web application. 

## Tech Stack
Node, TypeScript, Express.js

Requires **Node v.16**. If you're using **NVM**, just run in Terminal `nvm use`  to switch to v.16.

## Quick Start Guide
### 1. Environment variables
Add `.env` file to the root folder with the same content as in `.env.example`.

### 2.a. Development
```shell
npm install
npm run dev
```

### 2.b Production
Set `NODE_ENV=production` in your local `.env` file.
```shell
npm install
npm run build
npm start
```
