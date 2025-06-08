# Práctica 02 - Construir una imagen propia

En esta práctica crearás tu primera imagen personalizada de Docker.

1. Revisa el archivo `app.py` que contiene un pequeño script de Python.
2. Analiza el `Dockerfile` y observa las instrucciones `FROM`, `COPY` y `CMD`.
3. Construye la imagen ejecutando:
   ```bash
docker build -t mi-python-app .
   ```
4. Ejecuta un contenedor a partir de la imagen:
   ```bash
docker run --rm mi-python-app
   ```
5. Comprueba el mensaje que imprime el contenedor.

**Objetivo:** Aprender a crear imágenes a partir de un `Dockerfile` sencillo.
