# cvsergioparedes

Hoja de vida / portafolio web de **Sergio Paredes** — Desarrollador Full Stack especializado en eLearning/LMS (Moodle), ciberseguridad SOC e integración de IA (OpenAI, Anthropic, Groq).

Sitio estático (HTML, CSS y JavaScript vanilla), sin build ni dependencias — listo para GitHub Pages.

## Publicar con GitHub Pages

1. En GitHub: **Settings → Pages → Build and deployment → Source**: `Deploy from a branch`.
2. **Branch**: `main`, carpeta `/ (root)`.
3. Guardar. El sitio quedará disponible en `https://sergioparedesv.github.io/cvsergioparedes/`.

Todos los enlaces del sitio (`style.css`, `script.js`, `certificados/*.pdf`, `img/*`) son **rutas relativas**, así que funcionan igual en la URL por defecto de GitHub Pages o en un dominio propio.

### Dominio propio (opcional)

Si más adelante apuntas un dominio propio:

1. Agrega un archivo `CNAME` en la raíz de este repo con tu dominio (ej. `cv.tudominio.com`).
2. Configura el registro DNS correspondiente hacia GitHub Pages.
3. Actualiza en `index.html` las etiquetas `<link rel="canonical">`, `og:url` y la URL dentro del bloque `JSON-LD` (`schema.org/Person`) con el nuevo dominio.

## Estructura

- `index.html` — página única con todas las secciones.
- `style.css` / `script.js` — estilos e interactividad (idioma ES/EN, tema claro/oscuro, animaciones, acordeones de certificaciones).
- `certificados/` — PDFs reales de las certificaciones mostradas en la sección "Certificaciones".
- `img/` — capturas de proyectos.
