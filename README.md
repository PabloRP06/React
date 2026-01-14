# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

---

## 🛠️ Detalles del Proyecto

### 1. Lenguaje utilizado
Este proyecto está desarrollado con **JavaScript (JS)** utilizando el entorno de Vite para React. 
* *Nota:* No se utiliza TypeScript en esta versión específica.

### 2. ¿Qué es JSX?
Durante el desarrollo he utilizado **JSX** (JavaScript XML). 
Es una extensión de la sintaxis de JavaScript que permite escribir una estructura muy similar a HTML dentro de los archivos de código. Esto facilita la creación de interfaces de usuario en React porque:
* Permite mezclar lógica de programación y diseño visual en un mismo sitio.
* Se pueden usar variables y expresiones de JS dentro de las etiquetas usando llaves `{}`.
* Aunque parece HTML, es transformado por Vite en funciones de JavaScript que el navegador puede entender.

### 3. Instrucciones de Seguridad (Importante) ⚠️
Para mantener el repositorio ligero y profesional, **nunca se debe subir la carpeta `node_modules`**. 
* El archivo `.gitignore` ya está configurado para excluirla.
* Si descargas este proyecto en otro equipo, simplemente ejecuta `npm install` para regenerar los módulos localmente.

### 4. Cómo ejecutarlo
1. Instalar dependencias: `npm install`
2. Lanzar servidor: `npm run dev`
3. Abrir en el navegador: `http://localhost:5173/`
