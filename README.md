# ML Books — Descripción de la estructura del repositorio

Este documento describe la estructura actual del repositorio y el contenido principal de cada carpeta y archivo.

## Estructura general (raíz)

- `Hands-On-Machine-Learning/`: Materiales y notebooks relacionados con el libro "Hands-On Machine Learning".
- `Machine-Learning-with-PyTorch-and-Scikit-Learn/`: Materiales y notebooks relacionados con el libro "Machine Learning with PyTorch and Scikit-Learn".
- `.git/`: Metadatos internos de Git para control de versiones (no modificar manualmente).

A continuación se detalla el contenido de cada carpeta.

---

## `Hands-On-Machine-Learning/`

- `.gitignore`: Reglas para ignorar archivos temporales o generados (por ejemplo, checkpoints de notebooks).
- `Chapter-2/`: Recursos del capítulo 2
  - `.ipynb_checkpoints/`: Carpeta interna de Jupyter que almacena checkpoints automáticos de notebooks
    - `main-checkpoint.ipynb`: Último checkpoint del notebook principal
  - `main.ipynb`: Notebook principal del capítulo 2
  - `main-md.ipynb`: Variante del notebook (posiblemente exportación o versión con celdas en formato markdown)
  - `resume.md`: Resumen o notas del capítulo 2
- `Chapter-3/`: Recursos del capítulo 3
  - `main.ipynb`: Notebook principal del capítulo 3

---

## `Machine-Learning-with-PyTorch-and-Scikit-Learn/`

- `Chapter-2/`: Recursos del capítulo 2
  - `docs.txt`: Documento de texto con notas o instrucciones
  - `iris.ipynb`: Notebook con ejercicios o demostraciones (probablemente dataset Iris)

---

## Notas adicionales

- Este repositorio está versionado con Git. La carpeta `.git/` contiene la configuración de remoto y el historial de commits.
- Estructura detectada automáticamente mediante inspección del árbol de archivos. Si se añaden nuevos capítulos o materiales, actualice este `description.md` para mantener la documentación al día.

---

# ML Books — Repository Structure (English)

This document describes the current structure of the repository and the main contents of each folder and file.

## Top-level layout (root)

- `Hands-On-Machine-Learning/`: Materials and notebooks related to the book "Hands-On Machine Learning".
- `Machine-Learning-with-PyTorch-and-Scikit-Learn/`: Materials and notebooks related to the book "Machine Learning with PyTorch and Scikit-Learn".
- `.git/`: Git metadata for version control (do not modify manually).

Details for each folder are listed below.

---

## `Hands-On-Machine-Learning/`

- `.gitignore`: Rules to ignore temporary or generated files (e.g., Jupyter notebook checkpoints).
- `Chapter-2/`: Chapter 2 resources
  - `.ipynb_checkpoints/`: Jupyter internal folder storing automatic notebook checkpoints
    - `main-checkpoint.ipynb`: Latest checkpoint of the main notebook
  - `main.ipynb`: Main notebook for Chapter 2
  - `main-md.ipynb`: Variant of the notebook (possibly an export or markdown-focused version)
  - `resume.md`: Summary or notes for Chapter 2
- `Chapter-3/`: Chapter 3 resources
  - `main.ipynb`: Main notebook for Chapter 3

---

## `Machine-Learning-with-PyTorch-and-Scikit-Learn/`

- `Chapter-2/`: Chapter 2 resources
  - `docs.txt`: Text document with notes or instructions
  - `iris.ipynb`: Notebook with exercises or demonstrations (likely the Iris dataset)

---

## Additional notes

- This repository is tracked with Git. The `.git/` folder contains the remote configuration and commit history.
- Structure detected automatically by inspecting the file tree. If new chapters or materials are added, please update this `description.md` to keep the documentation accurate.
