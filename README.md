# 🐙 Git & GitHub - Fundamentos y Prácticas

> Repositorio dedicado al aprendizaje y aplicación de **Git** y **GitHub**, herramientas esenciales para el control de versiones y colaboración en desarrollo de software.

[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)
[![Curso](https://img.shields.io/badge/Nivel-Básico--Intermedio-blue?style=for-the-badge)](#)

---

## 📋 Descripción

Este repositorio documenta mi proceso de aprendizaje en **control de versiones distribuido** utilizando Git y GitHub. Incluye prácticas, comandos esenciales y flujos de trabajo colaborativo aplicados al desarrollo de software.

---

## 🎯 Objetivos del Curso

- Dominar los fundamentos de Git (inicialización, staging, commits, branches)
- Gestionar repositorios locales y remotos en GitHub
- Aplicar flujos de trabajo colaborativo (fork, clone, pull requests)
- Resolver conflictos de fusión (merge conflicts)
- Implementar buenas prácticas en mensajes de commit
- Utilizar branching strategy para organización del código

---

## 📚 Contenido del Repositorio

### **Fundamentos de Git**
- Inicialización de repositorios (`git init`)
- Configuración de usuario (`git config`)
- Estados del archivo (working directory, staging, repository)
- Commits y historial (`git commit`, `git log`)

### **Gestión de Ramas (Branching)**
- Creación y cambio de ramas (`git branch`, `git checkout`)
- Fusión de ramas (`git merge`)
- Estrategias de branching

### **Trabajo con GitHub**
- Conexión remoto (`git remote add origin`)
- Push y Pull (`git push`, `git pull`)
- Clonación de repositorios (`git clone`)
- Colaboración (Issues, Pull Requests, Code Review)

### **Resolución de Conflictos**
- Identificación de merge conflicts
- Estrategias de resolución
- Mejores prácticas

---

## 🛠️ Comandos Esenciales Aprendidos

```bash
# Configuración inicial
git config --global user.name "Gonzalo Galindo"
git config --global user.email "g.n.galindo@gmail.com"

# Flujo de trabajo básico
git init
git add .
git commit -m "Mensaje descriptivo del cambio"
git push origin main

# Gestión de ramas
git branch nombre-rama
git checkout nombre-rama
git merge nombre-rama
