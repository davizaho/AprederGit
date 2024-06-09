# 🛠️ Repositorio de Aprendizaje de Git

Bienvenido/a a **AprederGit** 🎉. Este es tu espacio para explorar, practicar y dominar Git, una de las herramientas más poderosas para el control de versiones y la colaboración en proyectos de software.

![Git Logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

## 📚 Índice

- [Sobre el Proyecto](#sobre-el-proyecto)
- [Comenzando](#comenzando)
- [Comandos Básicos de Git](#comandos-básicos-de-git)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Recursos Útiles](#recursos-útiles)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## 🧐 Sobre el Proyecto

Este repositorio está diseñado para ayudarte a aprender Git desde cero. Aquí encontrarás ejemplos de los comandos básicos, cómo se estructura un repositorio y algunos ejercicios prácticos. 

## 🚀 Comenzando

Para empezar a trabajar con este repositorio, sigue estos pasos:

1. **Clona el repositorio** en tu máquina local:
    ```bash
    git clone https://github.com/PhantomBCN/AprederGit.git
    ```
2. **Navega al directorio del proyecto**:
    ```bash
    cd AprederGit
    ```

## 📝 Comandos Básicos de Git

Aquí tienes una lista de comandos esenciales para empezar a trabajar con Git. Utilízalos como referencia rápida mientras exploras y aprendes.

### Inicialización y Configuración

- **Inicializar un repositorio Git en tu directorio**:
    ```bash
    git init
    ```

- **Configurar tu nombre y correo electrónico** (reemplaza "Tu Nombre" y "tu-email@ejemplo.com" con tus datos):
    ```bash
    git config --global user.name "Tu Nombre"
    git config --global user.email "tu-email@ejemplo.com"
    ```

### Trabajando con el Repositorio

- **Agregar archivos al área de preparación**:
    ```bash
    git add <archivo>
    ```
    Para agregar todos los archivos cambiados:
    ```bash
    git add .
    ```

- **Guardar los cambios en el repositorio**:
    ```bash
    git commit -m "Mensaje descriptivo de los cambios"
    ```

- **Visualizar el estado del repositorio**:
    ```bash
    git status
    ```

### Ramas y Fusión

- **Crear una nueva rama**:
    ```bash
    git checkout -b nueva-rama
    ```

- **Cambiar a una rama existente**:
    ```bash
    git checkout nombre-de-la-rama
    ```

- **Fusionar cambios de una rama a la rama actual**:
    ```bash
    git merge nombre-de-la-rama
    ```

### Actualización y Sincronización

- **Actualizar el repositorio local con los cambios del remoto**:
    ```bash
    git pull origin main
    ```

- **Enviar tus cambios al repositorio remoto**:
    ```bash
    git push origin main
    ```

### Otros Comandos Útiles

- **Mostrar el historial de commits**:
    ```bash
    git log
    ```

- **Ver diferencias entre el último commit y los cambios actuales**:
    ```bash
    git diff
    ```

## 📂 Estructura del Proyecto

La estructura de este repositorio es simple y está diseñada para facilitar tu aprendizaje.

