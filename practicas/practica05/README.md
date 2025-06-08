# Práctica 05 - Redes personalizadas

1. Crea una red bridge llamada `mired`:
   ```bash
docker network create mired
   ```
2. Ejecuta un contenedor `nginx` conectado a `mired` con el nombre `web`.
3. Ejecuta un contenedor `alpine` también en `mired` y desde él haz ping al contenedor `web` para comprobar la comunicación.
4. Inspecciona la red con `docker network inspect mired`.
5. Elimina los contenedores y la red al finalizar.

**Objetivo:** Comprender cómo funcionan las redes de Docker y la resolución de nombres entre contenedores.
