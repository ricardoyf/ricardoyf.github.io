# crear-apuntes

Instrucciones completas para que un agente cree apuntes de cualquier asignatura a partir de las fotos de una lección.

## Uso principal: fotos y enlace

1. Adjunta las fotos del temario en la conversación con tu agente.
2. Envía el enlace de esta página con este mensaje:

> Lee las instrucciones de esta página y crea los apuntes en HTML a partir de las fotos que te adjunto.

El agente encuentra todas las instrucciones en el contenido principal de la página. No necesitas rellenar un formulario, copiar un prompt largo ni explicar conversaciones anteriores.

El botón **Copiar mensaje con el enlace** utiliza la dirección actual de la página publicada, por lo que sigue funcionando cuando se traslada a otra ubicación.

## Instrucciones accesibles directamente

El prompt completo está escrito como HTML estático visible, con diez apartados y encabezados. Se puede leer sin ejecutar JavaScript, iniciar sesión, abrir desplegables o acceder a otro archivo. `prompt.md` ofrece la misma plantilla como texto Markdown.

El encargo es entregar un HTML completo y funcional con el contenido de las fotos. Los criterios sobre materia, nivel e idioma permiten empezar con el material disponible; se pide aclaración cuando hace falta para cubrir contenido esencial.

## Método de estudio

Primero organizar y clasificar; después pasar de pocas palabras a reglas, explicaciones y aplicaciones. Detectar los patrones del material y crear práctica, examen y tarjetas tipo Anki. Incluir gallego, castellano e inglés, impresión, HTML autónomo y conservación del progreso.

Las categorías, conceptos, dibujos, preguntas y tarjetas proceden de la nueva lección. No hay un temario predeterminado.

## Opciones adicionales

Después de todas las instrucciones hay dos apartados opcionales:

- **Personalizar o descargar una copia:** permite añadir datos específicos y copiar o descargar una versión personalizada.
- **Ejemplos de tarjetas:** demuestra la interacción con preguntas de matemáticas, inglés y francés. No modifica el encargo ni añade esas preguntas al prompt.

Estas opciones no forman parte del recorrido necesario para enviar las fotos y el enlace.

## Archivos y traslado

- `index.html`: página completa, con instrucciones estáticas y controles opcionales.
- `prompt.md`: instrucciones maestras en Markdown.
- `readme.md`: estas instrucciones de uso.
- `.nojekyll`: archivo para publicación estática.

Copia los cuatro archivos juntos a la carpeta o raíz del repositorio elegido. Los enlaces a archivos son relativos y el botón de compartir usa la dirección actual. La página no depende de una cuenta, un repositorio o una lección anterior.
