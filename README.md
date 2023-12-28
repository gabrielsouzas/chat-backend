# chat-backend - Servidor para um chat local com um aplicativo React Native

## Gerar package.json para as configurações do servidor

```shell
npm init -y
```

## Bibliotecas

### WebSocket

```shell
npm i ws
```

### Dotenv

```shell
npm i dotenv
```

## Scripts

Alterações no package.json

```json
"scripts": {
    "start": "node src/server.js", // Iniciar servidor
    "dev": "node --watch src/server.js" // Iniciar servidor com o node watch
  },
```

Comandos:

- Iniciar servidor:

```shell
npm start
```

- Iniciar servidor em desenvolvimento:

```shell
npm run dev
```
