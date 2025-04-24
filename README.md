# 🚀 1. Configurar Git con tu nombre y correo

Estos datos son necesarios para que Git sepa quién está haciendo los cambios.
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```
   > 📝 Nota: Solo se necesita hacer esto una vez en tu computadora.
    
# ✏️ 2. Hacer cambios y preparar archivos

Después de modificar archivos (por ejemplo: index.html, style.css, etc.), hay que agregarlos:
```bash
git add .
```
    > Este comando prepara todos los archivos modificados para guardarlos con un commit. 
    
# 💬 3. Hacer un commit con mensaje
```bash
git commit -m "Descripción corta del cambio"
```
    commit: Guarda los cambios localmente.
    -m: Significa mensaje. Va entre comillas una frase como: "Agregué el menú"  
    
# ⬆️ 4. Subir los cambios a GitHub
```bash
git push
```
    Esto sube los commits al repositorio en GitHub. Si es la primera vez, puede pedir usuario y contraseña o token.    
