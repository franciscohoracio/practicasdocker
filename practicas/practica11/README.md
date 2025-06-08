# Práctica 11 - Multi-stage y Docker Compose

1. Revisa el `Dockerfile` que compila una aplicación de Node.js en una primera etapa y genera una imagen liviana de producción.
2. El archivo `docker-compose.yml` usa la directiva `build` para construir la imagen y exponer el servicio por el puerto 8090.
3. Ejecuta:
   ```bash
docker-compose up --build
   ```
4. Comprueba la aplicación en `http://localhost:8090` (la carpeta `dist` deberá contener el código compilado).
5. Detén y elimina los contenedores con `docker-compose down`.

**Objetivo:** Integrar builds multi-stage dentro de Docker Compose.
