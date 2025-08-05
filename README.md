# PostgreSQL-Docker-DataGrip

## Comando para iniciar PostgreSQL en Docker

```bash
docker run --name postgres-db -e POSTGRES_PASSWORD=yourpassword -p 5432:5432 -d postgres
```

## Pasos para configurar DataGrip
1. Crear nueva conexión.
2. Host: localhost, Puerto: 5432, Usuario: postgres, Contraseña: yourpassword.
3. Probar conexión y guardar.

## Crear Base de Datos
``` bash
CREATE DATABASE my_first_database;
````

