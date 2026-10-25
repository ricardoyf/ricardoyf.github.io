# crear-apuntes

Una página para preparar instrucciones que conviertan fotos de una lección en apuntes interactivos. Clasificación primero; después palabras, frases, explicación, relaciones, tablas y tarjetas de repaso.

## Cómo usarla

1. Abre `index.html` en el navegador. También funciona sin conexión.
2. Elige un ejemplo —climas, inglés o francés— o escribe tu tema.
3. Copia el prompt completo o descárgalo.
4. Pégalo en la conversación con tu agente y adjunta las fotos de la lección.

La página configura el prompt; no analiza ni envía fotografías y no llama a servicios de inteligencia artificial. Los ejemplos de tarjetas son demostraciones y no guardan un calendario de repaso.

## Archivos

- `index.html`: página completa, con estilos, formulario, prompt y demostraciones.
- `prompt.md`: instrucciones maestras legibles directamente por personas y agentes.
- `readme.md`: estas instrucciones.
- `.nojekyll`: permite publicar como archivos estáticos.

## Idiomas y tarjetas

La interfaz del configurador está en castellano. El prompt pide los apuntes completos en gallego, castellano e inglés; permite elegir el idioma inicial.

Al preparar una lección de idiomas, distingue la lengua de la interfaz de la que se aprende. Las tarjetas de comprensión y producción tienen identidades y progresos separados: inglés→castellano no equivale a castellano→inglés, ni a francés→castellano.

## Publicación provisional

La web está en https://ricardoyf.github.io/clima/crear-apuntes/ y su código en la carpeta `crear-apuntes/` del repositorio `ricardoyf/clima`.

## Publicarla en un repositorio propio

Este directorio se puede trasladar sin modificar rutas:

1. Crea un repositorio público llamado `crear-apuntes`.
2. Coloca **el contenido de esta carpeta** en la raíz de la rama `main`.
3. En **Settings → Pages**, selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)**, y guarda.
4. Comprueba el despliegue antes de compartir la dirección. Una vez publicado en esa cuenta, será `https://ricardoyf.github.io/crear-apuntes/`.

La dirección del punto 4 es el destino previsto; esta documentación no afirma que el repositorio independiente ya exista.

Documentación: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
