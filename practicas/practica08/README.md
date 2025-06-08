# Práctica 08 - Variables y argumentos en Dockerfile

1. Revisa el `Dockerfile` que declara un argumento de construcción `APP_VERSION` y la variable de entorno `VERSION`.
2. Construye la imagen indicando un valor diferente de versión:
   ```bash
docker build --build-arg APP_VERSION=2.5 -t app-con-arg .
   ```
3. Ejecuta el contenedor para ver el mensaje con la versión:
   ```bash
docker run --rm app-con-arg
   ```

**Objetivo:** Entender el uso de `ARG` y `ENV` para parametrizar imágenes.
