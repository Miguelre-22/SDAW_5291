# Proyecto SDAW_5291

Este proyecto forma parte de la práctica de Entornos de Desarrollo, cuyo
objetivo es aprender a crear, configurar y gestionar un repositorio
utilizando Git y GitHub, además de comprender el uso de Node.js, Express
y la estructura básica de una aplicación web.

El proyecto consiste en una pequeña aplicación web que muestra un botón
y, al pulsarlo, aparece un mensaje de saludo personalizado: **"Hola
Miguel Re Ibarra"**.

## 🚀 Objetivos del proyecto

* Comprender el funcionamiento de un entorno Node.js.
* Crear un servidor web utilizando **Express**.
* Organizar un proyecto siguiendo una estructura clara.
* Documentar adecuadamente el proceso.
* Preparar el proyecto para ser versionado con Git y publicado en
  GitHub.

## 📂 Estructura del proyecto

```
SDAW_5291
├── index.html
├── script.js
├── package.json
├── server.js
└── README.md
```

## 🛠️ Requisitos previos

* Node.js instalado
* npm instalado
* Editor de código (VSCode recomendado)
* Git instalado

## 📦 Instalación del proyecto

### 1. Inicializar Node.js

```bash
npm init -y
```

### 2. Instalar Express

```bash
npm install express
```

## ▶️ Ejecutar el servidor

```bash
node server.js
```

o si configuraste el script:

```bash
npm start
```

Acceder desde el navegador a:

[http://localhost:3000](http://localhost:3000)

## 🖥️ Funcionamiento

Al pulsar el botón de la página web se muestra el mensaje:

```
Hola Miguel Re Ibarra
```

## 💻 Comandos Git utilizados

```bash
git init                # Inicializar repositorio local
git add .               # Añadir cambios
git commit -m "Mensaje inicial"  # Guardar cambios
git branch nombre_rama   # Crear rama
git checkout nombre_rama # Cambiar de rama
git merge otra_rama      # Integrar cambios
git push origin main     # Subir cambios al remoto
```

## 📷 Capturas y fragmentos de código

* Fragmento de `server.js`:

```javascript
const express = require('express');
const app = express();
const PORT = 3000;

app.use(express.static('.'));

app.listen(PORT, () => {
  console.log(`Servidor ejecutándose en http://localhost:${PORT}`);
});
```

* Fragmento de `script.js`:

```javascript
document.getElementById('boton').addEventListener('click', () => {
  alert('Hola Miguel Re Ibarra');
});
```

*(Aquí puedes añadir capturas de pantalla de VSCode mostrando commits, ramas y pull requests)*

## ✍️ Conclusiones personales

> Esta práctica me permitió comprender cómo funciona un flujo completo de **Git y GitHub**, la creación y gestión de ramas, la integración mediante pull requests y la publicación de un proyecto Node.js. Aprendí la importancia de documentar cada paso y mantener un historial de commits claro para facilitar el trabajo colaborativo.

## 👤 Autor

Miguel Re Ibarra

## 📚 Licencia

Licencia ISC generada automáticamente por npm.


## Información técnica añadida desde rama 2

A continuación, se muestra el historial de commits de la rama main en este punto:
f68e54b (HEAD -> Rama2_5291, origin/Rama2_5291) Añadir comentario en README.md para rama 2 de la etapa 7
7ee9df5 (origin/main, main) Añadir un comentario al fichero al fichero server.js
0afc7ca Cambiar el color de fondo del botón
5569243 Primer commit: etapa 4

## Información técnica añadida desde rama 1
En esta sección se describen los principales comandos de Git
utilizados durante la práctica:
- git init: (COMPLETAR)
- git add: (COMPLETAR)
- git commit: (COMPLETAR)
- git branch: (COMPLETAR)
- git merge: (COMPLETAR)
- git push: (COMPLETAR)

