# Práctica 12 - Publicación y CI/CD

1. Usa la imagen creada en la práctica anterior y súbela a un registro de contenedores propio (por ejemplo Docker Hub o GitHub Container Registry).
2. Crea un token de acceso y configura los comandos `docker login`, `docker tag` y `docker push`.
3. Diseña un flujo básico de CI/CD (por ejemplo con GitHub Actions) que construya la imagen multi-stage y la publique automáticamente en cada cambio de la rama principal.
4. Prueba que puedas descargar la imagen desde otro equipo con `docker pull`.

**Objetivo:** Completar el ciclo de construcción y despliegue automatizado utilizando Docker.
