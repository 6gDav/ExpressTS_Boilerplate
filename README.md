# ExpressTS Boilerplate

Minimalist boilerplate for ExpressJS with TypeScript.

# 🚀 What inside?

<ul>
  <li><b><a href="https://expressjs.com/">ExpressJS</a></b>: Backend framework. Based on <i>NodeJS</i>.</li>
  <li><b><a href="https://www.typescriptlang.org/">TypeScript</a></b>: Programing language for static typing.</li>
  <li><b><a href="https://tsx.is/">TSX</a></b>: It is modern esbuild based transpiler for <i>TypeScript</i> files.</li>
  <li><b><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules/">ES-Module</a></b>: <i>ESM</i> module system to able to import and export files.</li>
</ul>

# 🛠️ How to use?

## 📦 Installation 

* Clone this repository.
```bash
git clone https://github.com/6gDav/ExpressTS_Boilerplate.git
```
* Don't forget to rename `package.json` file if you renamed the whole file.

## 📈 Development

* Use this command to run the server in development mode:
```bash
npm run dev
```

* Use this command to build the server:
```bash
npm run build
```

* Use this command to run the server in production mode:
```bash
npm run start
```

* Use this command to stop the server:
```bash
npm run stop
```

* Use this command to restart the server:
```bash
npm run restart
```

* Use this command to run *TSX* server and watch the changes:
```bash
npx tsx watch src/server.ts
```

* Use this command to install the dependencies based on the `package.json` file:
```bash
npm install
```

* Use this command to undate teh dependencies:
```bash
npm update
```

# Basic packeges to download:

-- **[cors](https://www.npmjs.com/package/cors)**:  It is a middleware that allows you to enable Cross-Origin Resource Sharing (CORS) in your Express application.
```bash
npm install cors
```
```bash
npm install -D @types/cors
```

-- **[dotenv](https://www.npmjs.com/package/dotenv)**:  It is a zero-dependency module that loads environment variables from a `.env` file into `process.env`.
```bash
npm install dotenv
```

-- **[morgan](https://www.npmjs.com/package/morgan)**:  It is a middleware that logs HTTP requests to the console.
```bash
npm install morgan
```
```bash
npm install -D @types/morgan
```

-- **[helmet](https://www.npmjs.com/package/helmet)**:  It is a middleware that secures your app by setting various HTTP headers.
```bash
npm install helmet
```

-- **[zod](https://www.npmjs.com/package/zod)**:  It is a runtime type checking library for TypeScript.
```bash
npm install zod
```

-- **[http-errors](https://www.npmjs.com/package/http-errors)**:  It is a module that provides a set of HTTP error classes.
```bash
npm install http-errors
```
```bash
npm install -D @types/http-errors
```

-- **[axios](https://www.npmjs.com/package/axios)**:  Promise based HTTP client for the browser and node.js
```bash
npm install axios
```

-- **[jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)**:  An implementation of JSON Web Tokens.
This was developed against draft-ietf-oauth-json-web-token-08. It makes use of node-jws
```bash
npm install jsonwebtoken
```
```bash
npm install -D @types/jsonwebtoken
```

-- **[argon2](https://www.npmjs.com/package/argon2)**:  It's possible to hash using either Argon2i, Argon2d or Argon2id (default), and verify if a password matches a hash.
```bash
npm install argon2
```

