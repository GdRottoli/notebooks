Aquí tienes un borrador de README.md para ayudarte a configurar tu entorno de desarrollo de Python usando **uv**. Está diseñado para ser claro, directo y fácil de seguir, para que no tengas que preocuparte por los detalles técnicos.

# **Configuración del Entorno de Desarrollo con Python y UV**

Este README.md te guiará a través de los pasos necesarios para configurar tu entorno de desarrollo utilizando **uv**, una herramienta moderna y rápida para gestionar entornos y dependencias de Python.

## **1\. Instalación de uv**

Si aún no tienes uv instalado, puedes hacerlo de la manera más sencilla.

### **En macOS y Linux:**

Abre tu terminal y ejecuta el siguiente comando:

curl \-LsSf https://astral.sh/uv/install.sh | sh

### **En Windows:**

Abre PowerShell y ejecuta este comando:

irm https://astral.sh/uv/install.ps1 | iex

**Nota:** uv no requiere una versión de Python instalada en el sistema para funcionar. Sin embargo, para que puedas ejecutar el código, debes asegurarte de tener una versión de Python 3.8 o superior disponible en tu PATH.

## **2\. Creación del Entorno Virtual**

uv facilita la creación de un entorno virtual para tu proyecto. Esta es una buena práctica para mantener las dependencias aisladas y evitar conflictos.

Desde la raíz de tu proyecto, ejecuta:

`uv sync` 

Este comando creará una carpeta llamada .venv dentro de tu proyecto. Esta carpeta contiene una instalación aislada de Python y todas las dependencias que se especifican en pyproject.toml

## **3\. Activación del Entorno**

Una vez creado, debes activar el entorno para que tu terminal use la versión de Python y las librerías instaladas en él.

### **En macOS y Linux:**

`source .venv/bin/activate`

### **En Windows:**

`.venv\\Scripts\\activate`

Cuando el entorno esté activado, verás (.venv) al inicio del *prompt* de tu terminal.

## **5\. Desactivación del Entorno**

Cuando termines de trabajar en tu proyecto, puedes desactivar el entorno virtual simplemente escribiendo:

`deactivate`

Esto devolverá tu terminal a su configuración original.

## **Resumen de Comandos**

| Comando | Descripción |
| :---- | :---- |
| uv sync | Crea un entorno virtual con las dependencias del proyecto (.venv). |
| source .venv/bin/activate | Activa el entorno en Linux/macOS. |
| .venv\\Scripts\\activate | Activa el entorno en Windows. |
| uv pip install \-r requirements.txt | Instala las dependencias del proyecto desde un archivo de texto. |
| uv pip install \<paquete\> | Instala un paquete específico. |
| deactivate | Desactiva el entorno virtual. |