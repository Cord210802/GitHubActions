# Automatización de Pruebas con GitHub Actions

## Objetivo
Configurar y utilizar GitHub Actions para automatizar pruebas de scripts en Python, utilizando un repositorio base proporcionado.

## Pasos a Seguir

### 1. Preparación del Entorno de Trabajo
- **Fork del Repositorio**: Realiza un fork del repositorio de la clase en GitHub.
- **Clonar el Repositorio**: Clona el repositorio forked a tu máquina local.
- **Crear Branch**: Crea una nueva branch para trabajar en tus tareas.
- **Crear Carpeta**: Dentro de la carpeta `tareas`, crea una subcarpeta con tu nombre y primer apellido.

### 2. Configuración del Código
- **Copiar Código**: Copia el archivo de Python de la carpeta `códigos` a tu propia subcarpeta en `tareas`.

### 3. Configuración de GitHub Actions
- **Archivo YML**: En la carpeta `.github/workflows`, crea un archivo YML con tu nombre y apellido. Este archivo configurará el workflow que se ejecutará automáticamente cada vez que detecte que hiciste un cambio en tu carpeta al hacer un push (triger).
  - **Trigger**: Configura el archivo YML para que solo ejecute el action cuando se detecten cambios en tu carpeta de tareas.
- **Docker File**: Dentro de tu carpeta, crea un Dockerfile que configure el entorno necesario para ejecutar el archivo `.py`.

### 4. Ejecución de Pruebas Locales
- **Pruebas Locales**: Verifica que las pruebas se ejecutan correctamente en tu entorno local antes de hacer push al repositorio remoto.

### 5. Documentación
- **Archivo de Documentación**: Redacta un archivo `.txt` en tu carpeta. Este archivo debe explicar:
  - El propósito del proyecto.
  - Cómo se ejecutan las pruebas localmente.
  - La configuración del workflow de GitHub Actions.
  - Incluye cualquier información adicional que pueda ser útil para entender y ejecutar correctamente el proyecto.

## Criterios de Evaluación
- Correcta configuración y funcionalidad del workflow en GitHub Actions.
- Eficiencia de las pruebas unitarias implementadas.
- Claridad y completitud de la documentación proporcionada.

## Entregable
- Realiza un pull request de tu carpeta al repositorio original una vez completados todos los pasos.
