<a name="readme-top"></a>

<div align="center">
  <img src="logo.png" alt="logo" width="140" height="auto" style="border-radius:50%" />
  <br/>
  <h3><b>NETWORK SCRIPT PROJECT</b></h3>
</div>

# ✅ TABLE OF CONTENTS
- [📖 About the Project](#about-project)
  - [⚒️ Build With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run Tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🕹️ Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐ Show your Support](#support)
- [👏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📃 License](#license)

# 📖 NETWORK SCRIPT PROJECT <a name="about-project"></a>

**Network Script Project** is the first project in SENA's SysAdmin Network Curriculum.

## ⚒️ Built With <a name="built-with"></a>

This project was built using:
- HTML
- Markdown
- ShellScript
- Git
- GitHub

### Tech Stack <a name="tech-stack"></a>

- **HTML**
- **Markdown**
- **ShellScript**
- **Git**
- **GitHub**

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/es/docs/Web/HTML">HTML</a></li>
  </ul>
</details>

<details>
  <summary>Markdown</summary>
  <ul>
    <li><a href="https://markdown.es/sintaxis-markdown/">Markdown</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- **Network Scripting**: Automates network tasks using ShellScript.
- **Documentation**: Comprehensive documentation using Markdown.
- **Version Control**: Managed with Git and GitHub.

<p align="right"><a href="#readme-top">Back to top</a></p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps:

### Prerequisites

To run this project, you need the following tools:
- [VS Code](https://code.visualstudio.com/)
- [Git and GitHub](https://github.com/)
- [ShellScript](https://www.shellscript.sh/)

### Setup

1. **Linters**: A linter is a tool that analyzes your source code to flag programming errors, bugs, stylistic errors, and suspicious constructs.
   - **Why use linters?**
     - Catch syntax errors efficiently.
     - Maintain a consistent codebase.
     - Focus on solving problems instead of cleaning up code.

2. **Project Structure**:
   - Organize the project structure.
   - Copy `.hintrc.txt` and `.stylelintrc.json` files.
   - Verify and correct any errors.

3. **Configuration Files**:
   - Copy and configure `server.js`, `webpack.config.js`, and `.babelrc`.
   - Install dependencies required by these files.

### Install

Install the project dependencies:

```bash
# Lighthouse
npm install -g @lhci/cli@0.7.x

# Webhint
npm install --save-dev hint@7.x

# Stylelint
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x

# ESLint
npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x

# Webpack
npm init -y
npm install webpack webpack-cli --save-dev

# Webpack CSS Loader
npm install --save-dev style-loader css-loader

# Webpack HTML Loader
npm install --save-dev html-loader

# Webpack HTML Plugin
npm install --save-dev html-webpack-plugin

# Webpack Dev Server
npm install --save-dev webpack-dev-server