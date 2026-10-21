# Lukaris Outsourcing — sitio mejorado

## Archivos principales
- `index.html`: página principal con HTML semántico, CSS adaptable y JavaScript nativo.
- `assets/`: emblema y tipografías originales.
- `Privacidad.dc.html`, `Terminos.dc.html`, `Cookies.dc.html`: borradores iniciales para que los enlaces legales no queden rotos. **No deben publicarse sin completar los campos entre corchetes y revisar su contenido legal.**
- `previews/`: vista previa visual de escritorio y móvil.

## Qué se mejoró
- Se conserva la identidad de Lukaris: negro, dorado, marfil, emblema y tipografías originales.
- Se añadieron metadatos básicos para buscadores, datos estructurados del negocio con la información que aparece en la página, navegación a preguntas frecuentes y un bloque de preguntas frecuentes basado en el contenido existente.
- Se añadió un acceso flotante a WhatsApp y se mantuvieron las llamadas a la acción de planes y contacto.
- Se conserva el formulario con validación de campos y consentimiento; prepara un mensaje para WhatsApp y no lo envía automáticamente.
- Se mantienen los estilos responsive, foco visible de teclado y respeto a `prefers-reduced-motion`.

## Cómo verla
1. Descomprime el archivo ZIP completo.
2. Abre `index.html` en un navegador moderno.
3. Mantén la carpeta `assets` junto a `index.html`; no abras el HTML fuera de la carpeta.

También puedes iniciar un servidor local desde esta carpeta con `python -m http.server 8000` y abrir `http://localhost:8000`.

## Antes de publicar
- Completa y revisa los borradores de privacidad, términos y cookies; elimina los campos entre corchetes y confirma que reflejen el tratamiento real de datos y la entidad legal correcta.
- Confirma el teléfono de WhatsApp, correo, Instagram, horarios, nombres, planes y servicios.
- Añade el dominio definitivo y configura una imagen de vista previa social con URL absoluta cuando el dominio esté disponible.
- Comprueba la página alojada en móvil y escritorio, sus enlaces y formularios. No se ha configurado backend, envío automático, CRM, analítica ni gestor de contenidos.
- El formulario solo abre WhatsApp con un texto preparado; la persona decide si lo envía. El paquete no guarda consultas en una base de datos.
