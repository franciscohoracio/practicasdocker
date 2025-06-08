# Práctica 03 - Volúmenes de Docker

1. Crea un directorio en tu sistema anfitrión que contenga un archivo `datos.txt`.
2. Ejecuta un contenedor de `alpine` montando dicho directorio en `/datos`:
   ```bash
docker run -it --name prueba-vol -v $(pwd)/mi_datos:/datos alpine sh
   ```
3. Dentro del contenedor verifica el contenido de `/datos` y escribe nueva información en `datos.txt`.
4. Sal del contenedor y comprueba que el archivo de tu sistema anfitrión se ha actualizado.
5. Elimina el contenedor con `docker rm`.

**Objetivo:** Entender cómo funcionan los volúmenes para persistir información.
