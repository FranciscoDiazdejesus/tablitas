<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad 1 modulo 3 </title>
    <style>
    
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* Estilo de la barra  */
        .header {
            position: relative; /* Posicion del texto de fondo */
            background-color: #800080; /* Color de la barra */
            color: white; /* texto principal */
            padding: 20px; /* Espaciado */
            text-align: center; /* Aliniacion */
        }

        /* Texto de fondo */
        .background-text {
            position: absolute; /* Para posicionar detrás */
            left: 50%; 
            top: 50%; 
            transform: translate(-50%, -50%); /* Ajuste de posición */
            font-size: 100px; /* Tamaño del texto de fondo */
            color: rgba(255, 255, 255, 0.1); /* Color blanco con opacidad */
            pointer-events: none;
        }

        /* Estilo para el título principal */
        h1 {
            margin: 0; /* Quitar margen por defecto */
            z-index: 1; /* texto por encima del fondo */
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Tablas y estructuras</h1>
        <div class="background-text">Actividad</div>
    </div>

  <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #333;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #800080; /* Fondo morado */
            color: #FFFFFF; /* Texto blanco */
        }
        tr:nth-child(even) {
            background-color: #F5F5F5; /* Color de fondo alternativo */
        }
        /* Estilos para secciones de la tabla */
        .section {
            background-color: #e6e6e6; /* Fondo gris claro para secciones */
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Tabla de Conceptos HTML</h1>
    <table>
        <thead>
            <tr>
                <th>Concepto</th>
                <th>Descripción</th>
                <th>Concepto</th>
                <th>Descripción</th>
            </tr>
        </thead>
        <tbody>
            <tr class="section">
                <td colspan="4">Tablas y Formularios</td>
            </tr>
            <tr>
                <td>Tabla en HTML</td>
                <td>Un elemento que se utiliza para representar datos en forma de filas y columnas.</td>
                <td>Formulario en HTML</td>
                <td>Un conjunto de elementos que permiten la entrada de datos por parte del usuario.</td>
            </tr>
            <tr>
                <td>Etiqueta table</td>
                <td>Define la tabla en HTML.</td>
                <td>Etiqueta form</td>
                <td>Define un formulario para la entrada de datos.</td>
            </tr>
            <tr>
                <td>Atributos de table</td>
                <td>Proporcionan características adicionales a la tabla, como ancho y alto.</td>
                <td>Etiqueta input</td>
                <td>Define un campo de entrada para datos.</td>
            </tr>
            <tr class="section">
                <td colspan="4">Estructura de la Tabla</td>
            </tr>
            <tr>
                <td>Etiqueta tr</td>
                <td>Define una fila en una tabla.</td>
                <td>Etiqueta label</td>
                <td>Asocia un texto descriptivo a un campo de entrada.</td>
            </tr>
            <tr>
                <td>Atributo tr</td>
                <td>Proporciona características adicionales a una fila, como estilos.</td>
                <td>Etiqueta select</td>
                <td>Permite seleccionar una opción de un conjunto de opciones.</td>
            </tr>
            <tr>
                <td>Etiqueta td y th</td>
                <td>Definen celdas en la tabla, donde 'td' es para datos y 'th' para encabezados.</td>
                <td>Etiqueta textarea</td>
                <td>Permite la entrada de texto multilínea.</td>
            </tr>
            <tr>
                <td>Atributos de td y th</td>
                <td>Proporcionan características adicionales a las celdas, como alineación y colspan.</td>
                <td>Etiqueta fieldset, legend</td>
                <td>Agrupa elementos relacionados en un formulario, con un título.</td>
            </tr>
            <tr class="section">
                <td colspan="4">Tablas Avanzadas y Elementos</td>
            </tr>
            <tr>
                <td>Tablas avanzadas</td>
                <td>Uso de técnicas más complejas para crear tablas con más funcionalidad.</td>
                <td>Etiqueta meter</td>
                <td>Representa un valor escalar dentro de un rango conocido.</td>
            </tr>
            <tr>
                <td>Etiqueta thead</td>
                <td>Define el encabezado de una tabla.</td>
                <td>Etiqueta progress</td>
                <td>Representa el progreso de una tarea.</td>
            </tr>
            <tr>
                <td>Etiqueta tfoot</td>
                <td>Define el pie de una tabla.</td>
                <td>Etiqueta datalist</td>
                <td>Define una lista de opciones predefinidas para un campo de entrada.</td>
            </tr>
            <tr>
                <td>Etiqueta tbody</td>
                <td>Define el cuerpo de la tabla, donde se encuentran los datos.</td>
                <td>Etiqueta summary</td>
                <td>Proporciona un resumen de un contenido oculto.</td>
            </tr>
        </tbody>
    </table>

    <h1>Definiciones de Estructura Web</h1>

    <section>
        <h2>1. Contenedor (Wrapper)</h2>
        <p>El contenedor, o <strong>wrapper</strong>, es un elemento que envuelve todo el contenido de una página web. Se utiliza para centrar el contenido en la página y para aplicar estilos como márgenes y rellenos. Por lo general, se define mediante una etiqueta <code>&lt;div&gt;</code> con clases o identificadores CSS para controlar su ancho y alineación.</p>
    </section>

    <section>
        <h2>2. Cabecera (Header)</h2>
        <p>La cabecera, o <strong>header</strong>, es la parte superior de una página web. Suele contener elementos como el logotipo, el título del sitio y el menú de navegación. Se define típicamente con la etiqueta <code>&lt;header&gt;</code> y puede incluir otros elementos como <code>&lt;h1&gt;</code>, <code>&lt;nav&gt;</code>, y logotipos en imágenes.</p>
    </section>

    <section>
        <h2>3. Contenido (Content)</h2>
        <p>El contenido es la parte principal de una página web donde se muestra la información que se quiere transmitir. Esto puede incluir texto, imágenes, vídeos, formularios y otros elementos interactivos. Se suele definir con etiquetas como <code>&lt;main&gt;</code>, <code>&lt;section&gt;</code>, <code>&lt;article&gt;</code>, y <code>&lt;div&gt;</code>.</p>
    </section>

    <section>
        <h2>4. Menú (Menu)</h2>
        <p>El menú es un componente de navegación que permite a los usuarios moverse entre las diferentes secciones de un sitio web. Puede estar en la cabecera, lateral o en el pie de la página. Se define comúnmente con la etiqueta <code>&lt;nav&gt;</code>, que puede contener listas no ordenadas (<code>&lt;ul&gt;</code>) con enlaces (<code>&lt;a&gt;</code>).</p>
    </section>

    <section>
        <h2>5. Pie (Footer)</h2>
        <p>El pie de página, o <strong>footer</strong>, es la sección inferior de una página web que suele contener información adicional como derechos de autor, enlaces a políticas de privacidad, información de contacto y otros enlaces secundarios. Se define con la etiqueta <code>&lt;footer&gt;</code>.</p>
    </section>

    <section>
        <h2>6. Lateral (Sidebar)</h2>
        <p>La barra lateral, o <strong>sidebar</strong>, es una sección que se encuentra a un lado del contenido principal. Suele contener menús adicionales, enlaces, anuncios, o información complementaria. Se puede definir con una etiqueta <code>&lt;aside&gt;</code> o con <code>&lt;div&gt;</code> y se puede colocar tanto a la izquierda como a la derecha del contenido.</p>
    </section>

    <section>
        <h2>7. Etiqueta div</h2>
        <p>La etiqueta <code>&lt;div&gt;</code> es un elemento de bloque que se utiliza para agrupar otros elementos de la página y aplicar estilos a esos grupos. Es una de las etiquetas más versátiles en HTML, ya que no tiene un significado semántico específico, lo que permite su uso para crear estructuras personalizadas y dar estilo mediante CSS.</p>
    </section>

<h1> Identifica y describe los elementos que componen la estructuración semántica de una página web. </h1>
 <section>
        <h2>1. &lt;header&gt;</h2>
        <p>La etiqueta <strong>&lt;header&gt;</strong> representa la cabecera de un documento o sección. Puede contener elementos como logotipos, títulos y menús de navegación.</p>
    </section>

    <section>
        <h2>2. &lt;nav&gt;</h2>
        <p>La etiqueta <strong>&lt;nav&gt;</strong> contiene enlaces de navegación, permitiendo a los usuarios moverse entre las diferentes secciones de la página o del sitio.</p>
    </section>

    <section>
        <h2>3. &lt;main&gt;</h2>
        <p>La etiqueta <strong>&lt;main&gt;</strong> define el contenido principal del documento, excluyendo cabeceras, pies de página y barras laterales.</p>
    </section>

    <section>
        <h2>4. &lt;section&gt;</h2>
        <p>La etiqueta <strong>&lt;section&gt;</strong> representa una sección temática del contenido, que puede contener su propio encabezado.</p>
    </section>

    <section>
        <h2>5. &lt;article&gt;</h2>
        <p>La etiqueta <strong>&lt;article&gt;</strong> representa un contenido independiente y autocontenido que podría ser distribuido de forma independiente, como una entrada de blog o un artículo de noticias.</p>
    </section>

    <section>
        <h2>6. &lt;aside&gt;</h2>
        <p>La etiqueta <strong>&lt;aside&gt;</strong> contiene información relacionada que no es parte del contenido principal, como barras laterales o notas al margen.</p>
    </section>

    <section>
        <h2>7. &lt;footer&gt;</h2>
        <p>La etiqueta <strong>&lt;footer&gt;</strong> representa el pie de un documento o sección, que puede incluir información adicional como derechos de autor y enlaces a políticas de privacidad.</p>
    </section>

    <section>
        <h2>8. &lt;h1&gt;, &lt;h2&gt;, &lt;h3&gt;, etc.</h2>
        <p>Las etiquetas de encabezado, como <strong>&lt;h1&gt;</strong> y <strong>&lt;h2&gt;</strong>, representan títulos y subtítulos en el contenido, ayudando a estructurar la jerarquía de la información.</p>
    </section>

    <section>
        <h2>9. &lt;figure&gt; y &lt;figcaption&gt;</h2>
        <p>La etiqueta <strong>&lt;figure&gt;</strong> encapsula contenido gráfico, mientras que <strong>&lt;figcaption&gt;</strong> proporciona una descripción para ese contenido.</p>
    </section>

    <section>
        <h2>10. &lt;time&gt;</h2>
        <p>La etiqueta <strong>&lt;time&gt;</strong> representa una fecha o período de tiempo específico, útil para marcar fechas en artículos o eventos.</p>
    </section>

    <section>
        <h2>11. &lt;address&gt;</h2>
        <p>La etiqueta <strong>&lt;address&gt;</strong> contiene información de contacto para el autor de un documento o artículo, como dirección o correo electrónico.</p>
    </section>

    </body>

</html>
