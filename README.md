# EXCURSIONES EC — sitio web

Sitio estático en HTML, CSS y JavaScript. No requiere Node.js, base de datos ni proceso de compilación.

## Probar en tu computadora
1. Descomprime el proyecto.
2. Abre `index.html` en un navegador.
3. Para publicarlo, conserva `index.html` y todas las imágenes JPG en la misma carpeta.

## Publicar gratis con GitHub Pages
1. Entra a https://github.com/new e inicia sesión.
2. Crea un repositorio llamado `excursiones-ec-web` (puede ser público).
3. En la pantalla del repositorio, selecciona **Add file → Upload files**.
4. Arrastra `index.html` y todas las imágenes JPG de esta carpeta; confirma con **Commit changes**.
5. Abre **Settings → Pages**.
6. En **Build and deployment**, elige **Deploy from a branch**, selecciona `main` y la carpeta `/ (root)`, y guarda.
7. GitHub mostrará la dirección pública cuando termine la publicación.

## Publicar desde Git en Windows
Abre PowerShell dentro de esta carpeta y ejecuta (reemplaza `TU-USUARIO` por tu usuario de GitHub):

```powershell
git init
git add .
git commit -m "Publicar sitio EXCURSIONES EC"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/excursiones-ec-web.git
git push -u origin main
```

Luego activa GitHub Pages siguiendo los pasos 5–7. Si ya existe un repositorio, no ejecutes `git remote add origin` sin revisar primero `git remote -v`.

## Antes de publicar
- Verifica que el WhatsApp `+593 998 246 744` sea el número correcto.
- Revisa y confirma las tarifas referenciales y los servicios ofrecidos.
- Comprueba que tienes autorización para publicar todas las fotografías.
- Los enlaces de WhatsApp abren una conversación; el formulario no envía datos a un servidor.
