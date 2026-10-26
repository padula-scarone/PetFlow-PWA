# Registro de Dependencias - Backend

## Inicialización y Servidor
* **Express** (`npm install express`): Framework base para levantar el servidor y crear las rutas de la API REST.
* **TypeScript y Tipados** (`npm install -D typescript @types/node @types/express ts-node`): Motor para usar TypeScript estricto y diccionarios de traducción para que el IDE reconozca los comandos de Node/Express sin errores.

## Base de Datos
* **Prisma** (`npm install -D prisma`): Herramienta CLI para traducir el diseño DBML a PostgreSQL y gestionar la conexión con Supabase.

## Configuraciones
* **TS Config** (`npx tsc --init`): Se ajustó el `tsconfig.json` definiendo `"rootDir": "./src"` para el código fuente y `"outDir": "./dist"` para la compilación.

