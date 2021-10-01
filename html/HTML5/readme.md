## Nuevas secciones de HTML5
* HTML5 es un cambio grande en la web ya que agrega/cambia etiquetas de HTML y agrega más funcionalidades (extraído de MDN)
  * **Semántica:** Permite describir con mayor precisión cual es su contenido.
  * **Conectividad:** Permite comunicarse con el servidor de formas nuevas e innovadoras.
  * **Sin conexión y almacenamiento:** Permite a las páginas web almacenar datos localmente en el lado del cliente y operar sin conexión de manera más eficiente.
  * **Multimedia:** Nos otorga un excelente soporte para utilizar contenido multimedia como lo son audio y video nativamente.
  * **Gráficos y efectos 2D/3D:** Proporciona una amplia gama de nuevas características que se ocupan de los gráficos en la web como lo son canvas 2D, WebGL, SVG, etc.
  * **Rendimiento e Integración:** Proporciona una mayor optimización de la velocidad y un mejor uso del hardware.
  * **Acceso al dispositivo:** Proporciona APIs para el uso de varios compomentes internos de entrada y salida de nuestro dispositivo.
  * **CSS3:** Nos ofrece una nueva gran variedad de opciones para hacer diseños más sofisticados.

* Dentro de la mejora de semántica encontramos nuevas etiquetas que nos permiten describir mejor el contenido de nuestros documentos
* Podemos definir mejor la estructura de nuestro sitio utilizando las etiquetas **header** (encabezado), **nav** (barra de navegación), **aside** (contenido en otra posición del documento), **footer** (pie de nuestro sitio)

**Ejemplo:**
```html
<body>
  <header>
    <h1>Encabezado de nuestro sitio</h1>
  </header>
  <nav>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="bio.html">Bio</a></li>
    </ul>
  </nav>
  <aside>
    <p>Texto de la barra de costado del sitio</p>
  </aside>
  <section>
    <h2>Nueva sección de nuestro sitio</h2>
    <p>Contenido de nuestro sitio</p>
  </section>
  <footer>
    <p>Pie de nuestro sitio</p>
  </footer>
</body>
```

* Para describir un artículo, post o item de un foro podemos utilizar la etiqueta **article**
* Si queremos tener direcciónes del autor como contenido utilizamos la etiqueta **address**
* En caso de necesitar tener alguna fecha como contenido podemos utilizar la etiqueta **time**

**Ejemplo:**
```html
<body>
  <article>
    <p>Autor: Nombre del Autor</p>
    <time>Fecha de la publicación</time>
    <address>
      Datos sobre las direcciones del auto, tanto físicas como online
    </address>
  </article>
</body>
```

* Para más información podes leer la siguiente guía de [HTML5 en el MDN](https://developer.mozilla.org/es/docs/Sections_and_Outlines_of_an_HTML5_document)

[Ejercicio CV](../consignas/ejhtml5.md)<br>
[Ejercicio sitio01](../consignas/sitio01_html5)

* Referencias 
[HTML Semántico](https://curriculum.laboratoria.la/es/topics/html/02-html5/02-semantic-html)
[HTML en 15 minutos](https://www.freecodecamp.org/espanol/news/aprende-las-bases-de-html-para-principiantes-en-solo-15-minutos/)