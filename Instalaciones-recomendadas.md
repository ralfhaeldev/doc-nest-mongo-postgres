# Instalaciones recomendadas - Curso de Nest.js

<p align="center">
  <a href="http://nestjs.com/" target="blank">
    <img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" />
  </a>
</p>

## Herramientas recomendadas

- [Visual Studio Code](https://code.visualstudio.com/)
- [Postman](https://www.postman.com/downloads/)

## Opcionales

- [Table Plus](https://tableplus.com/)  
  Gestor de base de datos
- [Git](https://git-scm.com/)

```bash
git config --global user.name "Tu nombre"
git config --global user.email "Tu correo"
```

- [Node.js](https://nodejs.org/es/)

```bash
npm install --global yarn
```

- [Docker Desktop](https://www.docker.com/get-started)

### Descargar imágenes de Mongo y Postgres

```bash
docker pull mongo:5.0.0
docker pull postgres:14.3
```

---

## Extensiones de VSCode

- [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)

### Tema que estoy usando en VSCode

- [Tokyo Night](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

Para cambiar íconos de Angular por íconos de Nest:

```json
"material-icon-theme.activeIconPack": "nest",
```

---

## Instalaciones adicionales

- [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)  
  Permite crear clases a partir de JSON

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
- [Dotenv](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [Better Dockerfile Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-dockerfile-syntax)

---

## Wallpapers que uso

[Wallpapers Developer](https://drive.google.com/drive/folders/1ItU8rbSGJjnh2USOBGwaCo9nYKifPJ6m?usp=sharing)

---

## Crear proyecto con Vite

```bash
yarn create vite
# Elegir nombre del proyecto
# Seleccionar: Vanilla -> vanilla-ts
cd nombre-proyecto
yarn install
```

---

## Conectar MongoDB con Nest.js

[Documentación oficial](https://docs.nestjs.com/techniques/mongodb)

---

## Validar variables de entorno

[Paquete Joi - npm](https://www.npmjs.com/package/joi)

---

## Desplegar código en la nube

[Railway](https://railway.com/)

---

## Subir archivo

[File Upload en NestJS](https://docs.nestjs.com/techniques/file-upload)

---

## TypeORM

[Documentación TypeORM con Postgres](https://docs.nestjs.com/techniques/database)

---

## Decoradores personalizados

[Auth() y Guard()](https://docs.nestjs.com/custom-decorators#decorator-composition)

## Codigos de respuestas

[StatusCode](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Status)

## Docuemtnación Mongo

[MongoDB](https://docs.nestjs.com/techniques/mongodb)

## Conectar base de datos

[Postgres](https://docs.nestjs.com/techniques/database)

## Implementar sockets

[Sockets](https://docs.nestjs.com/techniques/database)

## Implementación de swagger

[Swagger](https://docs.nestjs.com/openapi/introduction)

## Construir imagen docker

```bash
docker build -t core-nest:v1 .
docker images
docker run -p 3000:3000 core-nest:v1
## Instalaciones para el proyecto
```

```bash
Yarn add @nestjs/typeorm typeorm
yarn add npm install pg
yarn add  class-validator class-transformer
yarn add @nestjs/mapped-types
yarn add bcrypt
yarn add -D @types/bcrypt
yarn add @nestjs/passport passport passport-jwt @nestjs/jwt
yarn add -D @types/passport-jwt

```
