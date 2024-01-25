# Relaciones y Semilla

Este proyecto previamente inicializado tiene todo lo necesario para trabajar con TypeScript, Express y Rest.

Proyecto con autenticación y autorización con protección de rutas y paginación así como relaciones y semilla para data en base de datos de `Mongo`.

### Para arrancar proyecto

1. Clonar .env.template a .env y configurar las variables de entorno
2. Ejecutar `npm install` para instalar las dependencias
3. En caso de necesitar base de datos, configurar el `docker-compose.yml` y ejecutar `docker-compose up -d` para levantar los servicios deseados.
4. Ejecutar `npm run seed` para levantar la `data` de la base de datos.
5. Ejecutar `npm run dev` para levantar el proyecto en modo desarrollo.

