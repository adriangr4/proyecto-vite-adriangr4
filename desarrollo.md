# Introducción

Esta práctica tiene como objetivo familiarizarse con Git y GitHub, aprender a trabajar con ramas y colaborar en proyectos utilizando Vite como entorno de desarrollo.

## Objetivos
- Aprender los comandos básicos de Git.
- Manejar el flujo de trabajo con ramas en Git.
- Practicar la colaboración con GitHub.
- Crear un proyecto básico utilizando Vite.

## Requisitos Previos
Antes de comenzar, asegúrate de tener lo siguiente instalado:
- Git
- Node.js
- Un editor de código (VS Code recomendado)
- Una cuenta en GitHub

# Desarrollo de la Práctica

## Parte 1: Configuración Inicial (15%)
1. Crear un repositorio en GitHub llamado `proyecto-vite-[tunombre]`.
2. Crear un directorio local para el proyecto.
3. Inicializar el proyecto con Vite:
    ```sh
    npm create vite@latest
    cd [nombre-proyecto]
    npm install
    ```
4. Inicializar Git en el directorio local y realizar el primer commit:
    ```sh
    git init
    git add .
    git commit -m "Primer commit"
    ```
5. Conectar el repositorio local con GitHub y subir el código:
    ```sh
    git remote add origin [URL-del-repo]
    git push -u origin main
    ```

## Parte 2: Trabajo con Ramas (25%)
1. Crear dos ramas nuevas:
    ```sh
    git branch desarrollo
    git branch feature-ui
    ```
2. En la rama `feature-ui`:
    - Modificar el `index.html` de Vite.
    - Realizar al menos 2 commits significativos.
3. En la rama `desarrollo`:
    - Añadir un nuevo componente.
    - Realizar al menos 2 commits significativos.

