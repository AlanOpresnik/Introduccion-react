Guía para Iniciar con React.js

1. Instalación de Node.js

Para trabajar con React.js, primero necesitas instalar Node.js, ya que incluye npm (Node Package Manager), que permite gestionar dependencias.

Instalación de Node.js:

Descarga Node.js desde la página oficial: https://nodejs.org/

Instala la versión LTS (recomendada para estabilidad).

Verifica la instalación ejecutando en la terminal:

node -v
npm -v

2. Configuración de Visual Studio Code

Se recomienda usar VS Code como editor de texto. Puedes descargarlo desde:
https://code.visualstudio.com/

Extensiones recomendadas:

ES7+ React/Redux/React-Native snippets: Atajos de código para React.
http://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets

Prettier - Code formatter: Formateador de código.
https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

ESLint: Linter para mejorar la calidad del código.
https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint



3. Creación de un Proyecto React

Existen dos maneras comunes de iniciar un proyecto en React: Vite y Create React App (CRA).

Opción 1: Crear un proyecto con Vite (Recomendado)

Vite es una alternativa rápida y moderna para crear proyectos de React.
npm create vite@latest
cd mi-proyecto
npm install
npm run dev

Opción 2: Crear un proyecto con Create React App (DEPRECADO)

npx create-react-app mi-proyecto
cd mi-proyecto
npm start

4. Estructura del Proyecto

Un proyecto de React generalmente tiene la siguiente estructura:

mi-proyecto/
│── node_modules/       # Dependencias instaladas
│── public/             # Archivos estáticos (favicon, imágenes, etc.)
│── src/                # Código fuente principal
│   ├── assets/         # Recursos estáticos (CSS, imágenes, fuentes, etc.)
│   ├── components/     # Componentes reutilizables
│   ├── pages/          # Páginas principales de la aplicación
│   ├── hooks/          # Custom hooks (opcional)
│   ├── context/        # Context API (opcional)
│   ├── services/       # Llamadas a APIs u otros servicios
│   ├── App.jsx         # Componente principal
│   ├── main.jsx        # Punto de entrada de la aplicación
│── .gitignore          # Archivos y carpetas a ignorar por Git
│── index.html          # Archivo HTML principal
│── package.json        # Configuración del proyecto y dependencias
│── vite.config.js      # Configuración de Vite
│── README.md           # Documentación del proyecto


5. Ejecutar el Proyecto

Para iniciar el servidor de desarrollo, usa:

npm run dev   # Si usaste Vite
npm start     # Si usaste Create React App

Esto abrirá la aplicación en http://localhost:5173/ (Vite) o http://localhost:3000/ (CRA).

6. Recomendaciones Adicionales

Usa Git para el control de versiones: git init

Instala dependencias adicionales según lo necesites: npm install react-router-dom
