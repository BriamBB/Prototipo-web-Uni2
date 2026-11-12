# Uni2

Comunidad universitaria para estudiantes de UCompensar. Proyecto de Emprendimiento.

- `index.html`: prototipo funcional (inicio de sesión, conectar, mentorías, eventos y foro).
- `landing.html`: página de presentación de la marca.

## Prototipo de demostración

- Sin base de datos ni servicios externos. Los datos son ficticios y las acciones se guardan solo en el navegador de cada persona (localStorage).
- El inicio de sesión y la verificación de correo son **simulados** y **no son seguros**. No uses contraseñas reales.
- Cuenta de prueba: `camila.demo@ucompensar.edu.co` / `Uni2demo!`
- Código de verificación del registro: `123456`

## Ejecutar en local

Abre `index.html` en el navegador, o en VS Code usa la extensión **Live Server** (clic derecho en `index.html` → *Open with Live Server*). Necesita internet solo para cargar las fuentes de Google.

## Publicar en GitHub Pages

1. Crea un repositorio vacío en GitHub.
2. En la carpeta del proyecto:
   ```
   git init
   git add .
   git commit -m "Prototipo Uni2"
   git branch -M main
   git remote add origin https://github.com/USUARIO/REPOSITORIO.git
   git push -u origin main
   ```
3. En GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → Branch: main, carpeta / (root) → Save**.
4. En uno o dos minutos la página queda en `https://USUARIO.github.io/REPOSITORIO/` (el prototipo) y `.../landing.html` (la presentación).

Para reiniciar los datos de prueba en tu navegador, borra los datos del sitio.
