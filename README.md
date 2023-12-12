<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

<p align="center">

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar

```
yarn install
```

3. Tener nest CLI Instalado

```
npm i -g @nestjs/cli
```

4. Levantar la base de datos

Abrir previamente docker desktop (en windows) y luego ejecutar en la raiz del proyecto:

```
docker-compose up -d
```

5. Clonar el archivo **.env.template** y renombrar a **.env** con las variables correspondientes

6. Ejecutar la app en Dev:

```
yarn start:dev
```

7. Reconstruir la BD con la semilla:

```
http://localhost:3000/api/v2/seed
```

## Stack usado

- MongoDB
- Nestjs
