# Proyecto HTML

Este repositorio contiene las tareas y páginas HTML para el curso.

Instrucciones rápidas (PowerShell):

1. Inicializar Git localmente:

   git init
   git add .
   git commit -m "Initial commit"

2. Crear repositorio remoto en GitHub y añadir remote `origin`. Por ejemplo:

   git remote add origin https://github.com/<usuario>/<repo>.git

3. Subir a GitHub:

   git branch -M main
   git push -u origin main

Alternativamente, usar la CLI de GitHub (`gh`):

   gh repo create <usuario>/<repo> --public --source=. --remote=origin --push

Notas:
- Reemplaza `<usuario>` y `<repo>` con tu usuario/nombre del repositorio.
- Asegúrate de tener configurado Git con tu nombre y correo:

  git config --global user.name "Tu Nombre"
  git config --global user.email "tu@correo.com"

- Si usas autenticación con token, puedes usar `gh auth login` o configurar un PAT.
