# My Community, My Culture

Página educativa de inglés A1 basada en el PDF universitario suministrado. HTML, CSS y JavaScript sin herramientas de compilación: editable directamente en VS Code y compatible con GitHub Pages.

## Ver y editar en VS Code

1. Abre esta carpeta con **File → Open Folder** en VS Code.
2. Abre `index.html` en tu navegador, o usa **Open with Live Server** si tienes la extensión Live Server.
3. Edita `index.html` para cambiar las secciones y referencias, `styles.css` para el diseño y `app.js` para los módulos y enlaces de actividades.
4. Guarda y actualiza el navegador. No necesitas instalar paquetes ni ejecutar una compilación.

También puedes iniciar una vista previa con `python -m http.server 5173` y abrir `http://localhost:5173` si tienes Python instalado.

## GitHub Pages

Repositorio: https://github.com/tauro9905/englishclass

Dirección del sitio cuando GitHub Pages esté publicado: https://tauro9905.github.io/englishclass/

Configuración: **Settings → Pages → Build and deployment → Deploy from a branch → main → / (root) → Save**. La publicación puede tardar unos minutos.

Para publicar futuras modificaciones desde VS Code, abre Source Control, revisa los cambios, crea un commit y usa **Sync Changes**. Los cambios enviados a `main` se publican automáticamente una vez activado Pages.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Contenido y origen

- Documento base: `assets/original-presentation.pdf` (15 páginas). No indica autor ni fecha.
- Introducción, cinco objetivos, cuatro módulos completos, inclusión, cinco actividades, evaluación, conclusión y cinco referencias.
- Las páginas 6–9 contienen imágenes con texto: se transcribieron visualmente sus metas, vocabulario, expresiones y actividades.
- Los cinco enlaces de actividades se asociaron según su posición visual en la página 11. **Culture Around the World** corresponde a Google Drive; **Culture Sharing**, al segundo Wordwall.
- El enlace de evaluación conserva el código de Wayground `49434213` del documento. Su vigencia depende del docente.
- Las referencias se reproducen como aparecen en el PDF; no se completaron autores, DOI, ediciones ni páginas faltantes por conjetura.
- Las traducciones al español, la tarjeta de práctica y los controles de interacción son adiciones de la adaptación web.

## Interacción y accesibilidad

Pestañas de módulos con navegación por flechas, Home y End; tarjetas de vocabulario que muestran su traducción; tarjeta de identidad con actualización inmediata; casillas de práctica; navegación por secciones y referencias desplegables. Diseño adaptable a móvil y escritorio, etiquetas de formulario, foco visible y respeto por movimiento reducido.

Los datos de práctica se mantienen únicamente en memoria en la pestaña. No se envían ni se guardan al recargar. Los enlaces externos abren los recursos originales; Google Docs/Drive pueden necesitar permisos y Wayground una sesión activa. Las fuentes de Google Fonts requieren internet y cuentan con alternativas locales del sistema.

## Ilustración

`assets/children.webp`: generada con la herramienta integrada ImageGen para este proyecto; seis personajes ficticios de Colombia, Brasil, Japón, India, Kenia y México, sin representar las nacionalidades mediante estereotipos. La nacionalidad es parte del concepto ficticio y no se infiere de la apariencia.

Prompt final: “Six fictional children from Colombia, Brazil, Japan, India, Kenya, and Mexico learning together outdoors around a large illustrated community map. A welcoming garden courtyard in a community neighborhood; simple leafy shapes and distant houses. Exactly six school-age children with varied skin tones, hair textures and hairstyles, in everyday casual clothing. Sophisticated editorial children's book illustration, gouache and cut-paper shapes, warm tactile paper grain. Landscape 3:2, all six children visible, warm sunny light. Terracotta, deep brown, ochre, cream and muted teal. No text, flags, logos or watermark.”

Los derechos sobre el PDF y los recursos enlazados pertenecen a sus respectivos titulares. La adaptación identifica las fuentes y no atribuye las ilustraciones añadidas a los autores de las referencias.
`assets/original-presentation.pdf` se conserva solo localmente y está excluido de Git. No se redistribuye en la web.
