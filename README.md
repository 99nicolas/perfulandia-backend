# Perfulandia Backend

Backend de Perfulandia organizado en microservicios con Spring Boot.

## Microservicios

### usuarioservice

Gestión de usuarios (id, nombre, correo y rol: admin, gerente o usuario).

- Java 17 · Spring Boot 3.4 (Web, Data JPA) · Lombok
- MySQL
- Puerto: `8081`

Ruta: `usuarioservice/usuarioservice`

## Ejecutar

1. Crea la base de datos `perfulandia_usuarios` en MySQL.
2. Ajusta `spring.datasource.*` en `src/main/resources/application.properties`.
3. Desde la carpeta del servicio:

```bash
./mvnw spring-boot:run
```
