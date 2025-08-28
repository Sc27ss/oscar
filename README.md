# Cardinals Consulting — Static Website

Sitio web estático listo para subir a GitHub.

## Estructura
- `index.html` redirige a `pages/homepage.html`
- `pages/` contiene las páginas internas
- `css/` estilos (Tailwind compilado en `main.css`)
- `public/` íconos, manifiesto y JS

## Cómo subir a GitHub (sin usar Git en tu PC)
1. Crea un repositorio vacío en GitHub (por ejemplo: `cardinals-consulting`).
2. Abre el repo en GitHub y haz clic en **Add file › Upload files**.
3. Arrastra **todos los archivos y carpetas** de este proyecto (no la carpeta en sí, sino su contenido).
4. Haz clic en **Commit changes**.

## Publicar en GitHub Pages
1. Ve a **Settings › Pages**.
2. En **Source**, selecciona **Deploy from a branch**.
3. **Branch:** `main` — **Folder:** `/ (root)` y guarda.
4. Espera a que se despliegue y visita la URL que te indique GitHub.

> Nota: No hay `package.json` porque este proyecto es 100% estático y no necesita build.
