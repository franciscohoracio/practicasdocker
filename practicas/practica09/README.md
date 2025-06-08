# Práctica 09 - Multi-stage build

1. Observa el `Dockerfile` que utiliza dos etapas: `builder` para compilar un programa en Go y una imagen final minimalista.
2. Construye la imagen ejecutando:
   ```bash
docker build -t app-multi-stage .
   ```
3. Comprueba el tamaño de la imagen resultante con `docker images app-multi-stage`.
4. Ejecuta el contenedor:
   ```bash
docker run --rm app-multi-stage
   ```

**Objetivo:** Crear imágenes optimizadas utilizando el proceso de multi-stage build.
