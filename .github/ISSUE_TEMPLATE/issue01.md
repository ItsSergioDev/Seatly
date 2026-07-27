# [E5] Configurar Drizzle y primera migración

## Resultado esperado

NestJS puede conectarse a PostgreSQL y ejecutar una migración inicial reproducible.

## Aprendizaje

- Diferencia entre esquema y migración.
- SQL generado por Drizzle.
- Conexión entre NestJS y PostgreSQL.
- Aplicación y reversión de cambios.

## Carga

5

## Responsable

Ambos mediante pair programming.

## Revisor

Revisión conjunta cambiando driver y navigator.

## Dependencias

- Workspace Nx creado.
- API NestJS funcionando.
- PostgreSQL disponible mediante Docker Compose.

## Criterios de aceptación

- Existe una migración versionada.
- La base puede crearse desde cero.
- La migración puede ejecutarse mediante un comando documentado.
- Ambos pueden explicar el SQL generado.
- CI puede validar la migración.

## Pruebas

- Eliminar la base local.
- Crear una base vacía.
- Ejecutar las migraciones.
- Comprobar las tablas resultantes.

## Documentación

- Actualizar README.
- Registrar la decisión Drizzle frente a Prisma.