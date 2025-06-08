# Práctica 07 - Volúmenes y variables en Compose

1. El archivo `docker-compose.yml` define un contenedor `postgres` con volumen persistente y variables de entorno.
2. Levanta el entorno con:
   ```bash
docker-compose up -d
   ```
3. Verifica que el volumen `dbdata` se haya creado y que puedes acceder a `http://localhost:8082` para administrar la base de datos con Adminer.
4. Detén y elimina el entorno con `docker-compose down -v` para borrar los volúmenes.

**Objetivo:** Utilizar volúmenes y variables de entorno en Docker Compose.
