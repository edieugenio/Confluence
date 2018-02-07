# Desarrollar documentación técnica con confluence

Confluence es una plataforma flexible con un rango de características y complementos que pueden ayudar a capturar, distribuir y actualizar documentación técnica.

## Crear su espacio de Documentación

Para crear su documentación inicial:

1. Haga clic en **Espacios** en la barra lateral de confluence, y haga clic en el botón **Crear espacio**.
2. Seleccione **Documentación en espacio** (hay un error en la traducción) y haga clic en Siguiente.
3. Escriba un nombre para su espacio y haga clic en **Crear**.

A continuación Confluence creará automáticamente un código para el espacio y mostrará una pantalla con la vista del espacio. Puede personalizar esta vista luego en cualquier momento.

## Ahorrar tiempo reutilizando contenido

Si hay algo que quiera utilizar várias veces en su espacio de documentación, tanto si es una palabra, oración o párrafo, una imágen, un número de versión de producto, o cualquier otra cosa, puede crearla una única vez e incluirla luego en tantas páginas como quiera (o utilizarlo en un encabezado o pie de página). Las inclusiones no solo le ahorran tener que reescribir lo mismo varias veces, también facilitan las cosas cuando hay que cambiar cosas, porque es mucho mejor cambiar la información en un único lugar.

Hay tres macros que permiten reutilizar contenido:
* La macro **Fragmento** para definir una sección reutilizable, o 'fragmento', en una página -añada contenido justo al lado de la macro, y podrá reutilizar este contenido en tantas páginas como desee.
* La macro **Incluir Fragmento** para incluir el contenido de un fragmento en otra página.
* La macro **Incluir Página** para inclur el contenido entero de una página en otra.

Por ejemplo, supongamos que crea notas de lanzamiento para cada una de las versiones iniciales de un producto, y desea incluir la introducción de cada página de notas de lanzamiento en una página de 'novedades'. Coloque cada nota de lanzamiento dentro de una macro Fragmento, y luego agregue una macro Incluir Fragmento en cada conjunto de notas de lanzamiento de la nueva página. Las intros aparecerán mágicamente en la página de novedades, y si se actualizan las notas de la versión, también se actualizarán automáticamnete en las novedades.

![](https://confluence.atlassian.com/confcloud/files/724765468/934718718/1/1502176540053/reuse%2520contentupdated.png)

1. **Fragmentos**: Las intros de esas páginas estan en macros Fragmentos
2. **Incluir Fragmentos**: estos son macros incluir fragmentos.

Otro ejemplo es una de las formas en que utilizamos ma macro Incluir página. Siempre que la elipsis () aparezca en nuestar documentación -por ejemplo, vaya a > Copiar en realidad es una macro Incluir página. Tenemos una página con esa imágen en ella, así que podemos incluirla cuando necesitamos una elipsis.
