# Práctica 04 - Publicar puertos

1. Observa el `Dockerfile` que usa la imagen `nginx` para servir el archivo `index.html`.
2. Construye la imagen con:
   ```bash
docker build -t web-nginx .
   ```
3. Ejecuta el contenedor mapeando el puerto 8080 del anfitrión al puerto 80 del contenedor:
   ```bash
docker run --rm -p 8080:80 web-nginx
   ```
4. Abre un navegador y accede a `http://localhost:8080` para ver la página.

**Objetivo:** Aprender a exponer servicios de un contenedor hacia el exterior.
