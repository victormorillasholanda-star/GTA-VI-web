# Centro de Información sobre GTA VI

Sitio web educativo de cinco páginas dedicado a ofrecer información detallada, noticias, personajes, recursos multimedia y un formulario de participación sobre el esperado lanzamiento de Grand Theft Auto VI en Vice City y el estado de Leonida.

## Autoría
- **Nombre y apellidos:** Víctor Morillas Martínez
- **Curso:** 1 DAM
- **Módulo:** Lenguaje de Marcas
- **Año:** 2026

## Sitio publicado
- **Web en GitHub Pages:** [Abrir sitio](https://tu-usuario.github.io/tu-repositorio/)
- **Repositorio:** [Abrir repositorio](https://github.com/tu-usuario/tu-repositorio)

## Estructura del proyecto
- `index.html`: Página principal con el logotipo, descripción del tema y resúmenes destacados.
- `blog.html`: Artículo detallado sobre el desarrollo y las novedades de Rockstar Games.
- `tabla.html`: Tabla estructurada de personajes y roles con accesibilidad y celdas combinadas.
- `galeria.html`: Galería multimedia que incluye mapa oficial, audio local, vídeo local con subtítulos, YouTube y Google Maps.
- `formulario.html`: Formulario completo de suscripción con validación HTML5 y múltiples tipos de control.
- `rss.xml`: Canal de sindicación de contenidos en formato XML.
- `css/estilos.css`: Hoja de estilos externa compartida.

## Tecnologías utilizadas
- HTML5 semántico
- CSS3 (Estilos básicos)
- XML y RSS
- Git y GitHub / GitHub Pages

## Características principales
- Navegación coherente y enlazada entre las cinco páginas.
- Uso riguroso de elementos semánticos (`header`, `nav`, `main`, `footer`, `article`, `section`).
- Tabla de datos accesible (`caption`, `thead`, `tbody`, `tfoot`, `scope`).
- Galería con múltiples formatos de imagen optimizados (JPG, WebP, SVG).
- Elementos multimedia locales e incrustados.
- Formulario robusto con validación nativa.
- Canal RSS validado.

## Validación
### HTML
*(Aquí puedes incluir más adelante una captura de pantalla de la validación W3C de tus páginas)*

### CSS
*(Captura de validación de estilos)*

### RSS
*(Captura de validación del RSS)*

## Dificultades encontradas
1. **Configuración de rutas relativas:** Asegurar que las imágenes, los audios y los vídeos cargaran correctamente tanto en local como en la ruta de despliegue de GitHub Pages. Se resolvió utilizando siempre rutas relativas limpias desde la raíz.
2. **Estructura semántica avanzada:** Organizar correctamente las etiquetas dentro de los artículos y el formulario asegurando la accesibilidad con `label`, `for` e `id`. Se resolvió repasando la especificación oficial de HTML5.
3. **Control de versiones progresivo:** Planificar el historial de commits para reflejar de forma realista la evolución del desarrollo del sitio web. Se resolvió realizando commits frecuentes por cada módulo finalizado.

## Decisiones técnicas
- **Organización de archivos:** Se han separado los recursos multimedia en carpetas específicas (`img/`, `audio/`, `video/`, `css/`) para mantener un orden óptimo.
- **Plantilla común:** Se ha mantenido una cabecera, un menú de navegación y un pie de página idénticos en todas las páginas para dar cohesión visual.
- **Formatos de imagen:** Se han seleccionado JPG y WebP para optimizar el peso de las fotografías y SVG para el logotipo e iconos vectoriales.

## Fuentes y licencias
- Imágenes y recursos informativos obtenidos con fines educativos para el módulo de Lenguaje de Marcas del curso 2026.
```[cite: 26, 27, 28]

---

### ¿Qué haces ahora con esto?
1. Guarda el archivo **`README.md`** en VS Code.
2. Vuelve a la terminal y ejecuta los comandos finales para guardar este último cambio y subirlo todo a GitHub:
   ```bash
   git add README.md
   git commit -m "Añade la documentación del proyecto en README.md"
   git push -u origin main