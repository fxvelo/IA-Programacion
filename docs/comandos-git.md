Comandos más usados día a día

bash
git status                 # Ver qué hay sin agregar
git add .                  # Agregar TODO lo que cambió
git add archivo.py         # Agregar solo un archivo
git commit -m "mensaje"    # Crear commit con mensaje
git push                   # Subir commits al remoto
git pull                   # Bajar cambios del remoto
git log --oneline          # Ver historial corto
git diff                   # Ver cambios sin commit


Flujo habitual de trabajo

git status
git add . (o git add archivo)
git commit -m "Descripción clara del cambio"
git push


Comandos que necesitás ejecutar ahora (primer push)

bash
# 1. Conectar con GitHub (si todavía no lo hiciste)
git remote add origin https://github.com/TU-USUARIO/nombre-del-repo.git

# 2. Subir la rama principal
git branch -M main
git push -u origin main



Tips rápidos
Cambiá TU-USUARIO y nombre-del-repo por los tuyos reales.
Si ya hiciste git init y todavía no tenés nada en GitHub, creá el repo vacío en GitHub.com (sin README ni .gitignore) y luego usá los comandos de arriba.
Después del primer push, usás solo: git add . && git commit -m "msg" && git push

