# Práctica 06 - Docker Compose básico

1. Analiza el archivo `docker-compose.yml` que define un servicio web y un servicio `redis`.
2. Levanta los servicios ejecutando:
   ```bash
docker-compose up -d
   ```
3. Comprueba que ambos contenedores están en ejecución con `docker-compose ps`.
4. Accede al navegador en `http://localhost:8081` para ver el contenedor `nginx`.
5. Detén y elimina los servicios con `docker-compose down`.

**Objetivo:** Introducir Docker Compose para orquestar múltiples contenedores.
