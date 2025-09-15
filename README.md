# GitInit-Guide

README.md

# Nombre de tu Proyecto

Una breve descripción de tu proyecto. ¿Qué hace? ¿Cuál es su propósito?

## Empezando con Git

Esta guía te muestra cómo empezar a usar Git en un sistema Linux, desde la configuración inicial hasta tu primer commit.

### Prerrequisitos

Asegúrate de tener Git instalado en tu sistema. Si no es así, puedes instalarlo usando el gestor de paquetes de tu distribución (por ejemplo, `sudo apt install git` en Ubuntu).

### Configuración inicial de Git

Antes de empezar, debes configurar tu identidad en Git. Estos comandos asocian tu nombre y correo electrónico con cada commit que realices.

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu_correo@ejemplo.com"
Si usas Visual Studio Code como tu editor, puedes configurarlo para que se abra automáticamente cuando Git lo necesite (por ejemplo, para escribir un mensaje de commit).


git config --global core.editor "code --wait"
Iniciar el repositorio local
Navega hasta el directorio de tu proyecto y usa el siguiente comando para inicializar un nuevo repositorio de Git. Esto creará una carpeta oculta llamada .git.


cd /ruta/a/tu/directorio
git init
Agregar y hacer el primer commit
Después de crear o modificar tus archivos, agrégalos al área de staging y luego realiza el primer commit.


git add .
git commit -m "Primer commit: inicialización del proyecto"
