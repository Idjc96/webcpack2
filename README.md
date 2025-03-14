<a name="readme-top"></a>

<div align="center">
  <img src="logo.png" alt="Logo del proyecto" width="140" height="auto" style="border-radius:50%" />
  <br/>
  <h3><b>PROYECTO DE SCRIPTS DE ANALISIS Y DESARROLLO DE SOFTWARE</b></h3>
</div>

# 📖 PROYECTO DE SCRIPTS DE RED <a name="about-project"></a>

**Proyecto de Scripts de Red** es el primer proyecto del programa de analisis y desarrollo de Software del SENA. Este proyecto automatiza tareas y sirve como base para aprender prácticas esenciales de desarrollo.

## ⚙️ Construido con <a name="built-with"></a>

### Tecnologías Principales
- **HTML** - Estructura de documentación
- **JavaScript** - Lógica de automatización
- **CSS** - Estilos para la documentación
- **Git & GitHub** - Control de versiones
- **Webpack** - Empaquetado de recursos

### Stack Técnico <a name="tech-stack"></a>

<details>
  <summary>Cliente</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/es/docs/Web/HTML">HTML5</a> para estructura web</li>
  </ul>
</details>

<details>
  <summary>Herramientas</summary>
  <ul>
    <li><a href="https://markdown.es/sintaxis-markdown/">Markdown</a> para documentación</li>
    <li><a href="https://webpack.js.org/">Webpack</a> para gestión de módulos</li>
  </ul>
</details>

### Características Clave <a name="key-features"></a>
- 🛠️ **Automatización de Red**: Scripts en Shell para tareas de diagnóstico
- 📚 **Documentación Detallada**: Guías técnicas en Markdown
- 🔄 **Control de Versiones**: Flujo de trabajo con Git/GitHub
- ⚡ **Optimización**: Configuración de Webpack para eficiencia

<p align="right"><a href="#readme-top">Volver al inicio</a></p>

## 🚀 Comenzando <a name="getting-started"></a>

### Requisitos Previos <a name="prerequisites"></a>
- Editor de código como [VS Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/) instalado
- Cuenta en [GitHub](https://github.com)

### Configuración Inicial <a name="setup"></a>
1. Clona el repositorio:
```bash
git clone https://github.com/Idjc96/webcpack2.git

# Lighthouse para auditoría de rendimiento
npm install -g @lhci/cli@0.7.x

# Webhint para análisis HTML
npm install --save-dev hint@7.x

# Stylelint para validación CSS
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x

# ESLint para análisis JavaScript
npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x

# Webpack y complementos
npm install webpack webpack-cli --save-dev
npm install --save-dev style-loader css-loader html-loader html-webpack-plugin webpack-dev-server

# Ejecuta todos los linters
npx stylelint "**/*.{css,scss}"
npx hint .
npx eslint .

Autores <a name="authors"></a>