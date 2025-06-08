# Etapa de construcción
FROM node:20 AS build
WORKDIR /app
COPY . .
RUN npm install && npm run build

# Etapa de producción
FROM node:20-slim
WORKDIR /app
COPY --from=build /app/dist ./dist
EXPOSE 8080
CMD ["node", "dist/index.js"]
