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

## Parte 3: Colaboración (30%)
### Pasos del Propietario del Repositorio
1. Añadir colaboradores en GitHub desde `Settings > Collaborators`.
2. Asegurarse de que aceptan la invitación.

### Pasos del Colaborador
1. Aceptar la invitación de colaboración.
2. Clonar el repositorio:
    ```sh
    git clone [URL-del-repo]
    ```
3. Crear y cambiar a una nueva rama:
    ```sh
    git checkout -b feature-nav-[tunombre]
    ```
4. Realizar modificaciones y commits:
    ```sh
    git add .
    git commit -m "Cambios en la navegación"
    ```
5. Subir la rama al repositorio:
    ```sh
    git push origin feature-nav-[tunombre]
    ```
6. Crear un Pull Request en GitHub.

### Pasos del Propietario para Gestionar el PR
1. Revisar el Pull Request en la pestaña `Pull requests`.
2. Aprobar o solicitar cambios.
3. Hacer `merge` una vez aprobado y borrar la rama si ya no se necesita.

## Parte 4: Integración Final (20%)
1. Realizar `merge` de la rama `desarrollo` a `main`.
2. Resolver cualquier conflicto que surja.
3. Hacer un push final a GitHub:
    ```sh
    git push origin main
    ```

## Parte 5: Documentación (10%)
Se debe crear un archivo `README.md` que contenga:
- Descripción del proyecto.
- Capturas de pantalla del proceso.
- Listado de comandos utilizados.
- Diagrama del flujo de trabajo seguido.