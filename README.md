<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# CRUD básico con NestJS

Este proyecto es un ejemplo de un CRUD básico implementado con NestJS.

### Uso
Para ejecutar la aplicación, utiliza el siguiente comando:

```
npm run start
```

Esto iniciará la aplicación y la hará disponible en http://localhost:3000.

Luego, ejecutar lo siguiente para generar datos de ejemplo

```
http://localhost:3000/seed
```

La aplicación implementa las siguientes rutas:

- GET /cars: Retorna una lista de todos los elementos en la base de datos.
- GET /cars/:id: Retorna un elemento específico según el id.
- POST /cars: Crea un nuevo elemento en la base de datos.
- PATCH /cars/:id: Actualiza un elemento específico según el id.
- DELETE /cars/:id: Elimina un elemento específico según el id.