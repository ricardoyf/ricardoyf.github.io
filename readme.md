# crear-apuntes

Creador de instrucciones para preparar apuntes interactivos a partir de fotos de cualquier asignatura. El método es estable: organizar y clasificar primero, profundizar por niveles, detectar patrones, practicar, examinarse y repasar con tarjetas. El temario se obtiene de las fuentes de cada encargo.

## Uso

1. Abre `index.html`. El formulario empieza sin asignatura, tema ni edad.
2. Completa los datos que conozcas o deja que el agente los identifique en las fotos.
3. Copia el prompt completo o descárgalo.
4. Pégalo en tu agente y adjunta las fotos de la nueva lección.

Los accesos de inglés y francés configuran la modalidad de aprendizaje; no añaden vocabulario, preguntas ni una lección de ejemplo.

El creador prepara instrucciones. Las fotos se aportan al agente que realizará los apuntes.

## Una estructura adaptable al temario

- El mapa parte de las categorías, partes, etapas, procedimientos o relaciones reales de las fotos.
- Los cuatro escalones permiten pasar de pocas palabras a reglas, explicaciones y aplicaciones.
- Las tablas aparecen cuando hay aspectos comparables. Otros patrones pueden necesitar secuencias o diagramas.
- Los ejercicios y las tarjetas proceden de lo estudiado, sin cantidades ni contenidos fijos.
- Se conserva el orden cuando expresa cronología, sintaxis, procedimiento o posición significativa.
- Cada nueva lección tiene su propia identidad y su propio progreso.

## Idiomas y objetos de estudio

Las interfaces solicitadas son gallego, castellano e inglés; el idioma inicial se puede elegir. El idioma del material puede detectarse automáticamente.

La traducción de la interfaz conserva las oraciones que se analizan, las fórmulas, los símbolos y el vocabulario objetivo. En aprendizaje de idiomas, cada lengua y dirección de las tarjetas tiene su propio progreso.

## Demostraciones opcionales

El apartado desplegable de ejemplos contiene pequeñas tarjetas de matemáticas, inglés y francés. Sirve para probar la interacción de mostrar y ocultar una respuesta. No programa repasos.

Cambiar de ejemplo no modifica el formulario ni el prompt. Las preguntas de las demostraciones nunca se incorporan automáticamente al encargo.

## Archivos y traslado

- `index.html`: configurador autónomo, con estilos, instrucciones y demostraciones incorporados.
- `prompt.md`: plantilla maestra, sin contenido de una asignatura concreta.
- `readme.md`: estas instrucciones.
- `.nojekyll`: archivo para publicación estática.

Para trasladar la página, copia estos cuatro archivos juntos a la carpeta o raíz del repositorio elegido. Los enlaces usan rutas relativas y no dependen de una cuenta, un repositorio o una lección anterior. El configurador no necesita servidor, bibliotecas externas ni conexión para generar el prompt.

La descarga del prompt contiene los datos actuales del formulario y todas las instrucciones maestras. El enlace a `prompt.md` ofrece la plantilla neutra sin personalizar.
