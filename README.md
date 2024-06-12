# Fitbase landing page

#### Introducción
Este proyecto es una aplicación web desarrollada con [Astro](https://astro.build/), un framework moderno para la creación de sitios web rápidos y eficientes. 

#### Estructura del proyecto
La estructura del proyecto es la siguiente:

```
├── .github/
│   └── workflows/
├── .husky/
│   ├── commit-msg
│   ├── pre-commit
│   └── prepare
├── .vscode/
├── dist/
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   └── styles/
│       └── env.d.ts
├── .editorconfig
├── .eslintignore
├── .eslintrc
├── .gitignore
├── .prettierignore
├── .prettierrc
├── astro.config.mjs
├── commitlint.config.js
├── package.json
├── pnpm-lock.yaml
├── README.md
└── tsconfig.json
```

#### Instalación
Para instalar y configurar el proyecto, sigue estos pasos:

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/immune-institute-ceb/fitbase.git

   cd fitbase
   ```

2. **Instalar las dependencias:**
   ```bash
   pnpm install
   ```

#### Scripts Disponibles
En el archivo `package.json` se definen varios scripts para diferentes tareas. Los más relevantes son:

- `dev`: Para iniciar el servidor de desarrollo.
- `build`: Para construir la versión de producción del sitio.
- `preview`: Para previsualizar la versión de producción.
- `lint`: Para analizar el código en busca de errores y problemas de estilo.

Ejecuta estos scripts usando `pnpm`:

```bash
pnpm run dev
pnpm run build
pnpm run preview
pnpm run lint
```

#### Estructura de Carpetas

- **.github/workflows**: Contiene configuraciones para integración continua (CI).
- **.husky**: Scripts de Git hooks para automatizar tareas antes de los commits.
- **.vscode**: Configuraciones específicas de Visual Studio Code.
- **dist**: Carpeta generada para la salida de producción.
- **node_modules**: Módulos de Node.js instalados.
- **public**: Archivos públicos y estáticos.
- **src**: Contiene el código fuente de la aplicación.
  - **assets**: Recursos como imágenes, fuentes, etc.
  - **components**: Componentes reutilizables de la interfaz.
  - **layouts**: Plantillas de diseño.
  - **pages**: Páginas del sitio web.
  - **styles**: Estilos CSS/SCSS.
- **.editorconfig**: Configuración del editor de texto.
- **.eslintignore**: Archivos y directorios ignorados por ESLint.
- **.eslintrc**: Configuración de ESLint.
- **.gitignore**: Archivos y directorios ignorados por Git.
- **.prettierignore**: Archivos y directorios ignorados por Prettier.
- **.prettierrc**: Configuración de Prettier.
- **astro.config.mjs**: Configuración de Astro.
- **commitlint.config.js**: Configuración de Commitlint.
- **package.json**: Información del proyecto y scripts.
- **pnpm-lock.yaml**: Archivo de bloqueo de versiones para `pnpm`.
- **README.md**: Documentación del proyecto.
- **tsconfig.json**: Configuración de TypeScript.

#### Desarrollo
Para desarrollar y hacer cambios en el proyecto, inicia el servidor de desarrollo:

```bash
pnpm run dev
```

Esto iniciará el servidor y podrás ver los cambios en tiempo real en tu navegador en `http://localhost:4321/fitbase`.
