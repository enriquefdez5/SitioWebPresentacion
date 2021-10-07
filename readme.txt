El sitio web está formado por 4 archivos en formato html. 
    Index.html: Contiene mi información biográfica, una breve descripción sobre mi y una 
                anotación sobre mi mascota. También contiene elementos comunes como el menú de 
                navegación o un pie de página con mi información de contacto.
    Aficiones.html: Contiene información sobre mis aficiones, principalmente se habla del deporte 
                    y las tres modalidades que más practico o he practicado como son el fútbol, 
                    triatlón y frontón. Se incluyen datos representados en una tabla, 
                    así como el menú de navegación y pie de página.
    Musica.html: En este fichero se habla de mis gustos musicales, se incluye un video de un tema 
                me gusta mucho y un audio de otro tema de distinto género que también me gusta mucho. 
                Además, vuelven a estar presentes elementos comunes como el menú de navegación y el 
                pie de página.
    Pueblo.html: En este documento se habla sobre mi pueblo y se incluyen lugares de interés del mismo,
                 con una breve descripción del motivo por el que son impotantes. También se incluye 
                el menú de navegación y el pie de página.

    La carpeta css contiene las hojas de estilo que son utilizadas para aplicar un diseño sobre 
    los elementos de los documentos descritos anteriormente. 
    El estilo elegido ha sido un estilo simple con un layout que sigue el flujo normal del contenido, 
    aunque en algunas situaciones la distribución de los elementos es modificada, como en el caso de 
    la imágen flotando a la derecha, el elemento aside o los lugares de interés documento pueblo.html, en el que se ha 
    intentado que cada lugar tenga un bloque con una imagen y una descripción del mismo.
    Contiene 5 hojas de estilo:
        aside_left.css: Hoja de estilo para los elemento aside del index.html. Colocará el elemento a la derecha del contenido principal.
        audio.css: Hoja de estilo para los elementos audios.
        direccion.css: Utilizado para aplicar estilo al elemento address que aparece en el 
                        footer común para todos los html. Básicamente aplica cursiva al texto.
        estilo.css: Es la hoja de estilo principal del sitio web. Contiene características 
                    comunes para todos los html, con tipo de letra del body, color del fondo de 
                    la página web o representación de los enlaces. También incluye el estilo 
                    del menú de navegación, un menú fijo en la parte superior de la pantalla.
        imagen_flotando_izquierda.css: Hoja de estilo para colocar las imagenes flotando a la izquierda.
        tablas.css: Hoja de estilo para dar diseño a la única tabla del documento. Da estilo a la tabla 
                    y su contenido.
        tajetas_secciones.css: Convierte las secciones en una especie de tarjeta, en la que las imagenes estarán a la izquierda con su pie de página y 
                                el contenido se mostrará a la derecha, todo marcado con un borde.
        video.css: Hoja de estilo para el elemento video.

    Por último, la carpeta Multimedia contiene las imágenes, audios y videos necesarios.



Consideraciones a tener en cuenta durante la realización de la práctica.
    - Atributo accessKey: Se han utilizado accessKey para los enlaces. Esta práctica favorece la interación con la web mediante el teclado, pero también es una práctica que puede 
                            provocar confusión al usuario ya que los atajos pueden ser conflictivos con algunos atajos del navegador o del SO, por lo que algunas herramientas,
                             como Wave, marcan como advertencia el uso de este atributo.
    - Atributo tabindex: Wave también marca como advertencia el uso de este atributo. Además, webaim no recomienda su uso con un valor de 1 o +(positivo), ya que se altera 
                            el orden lógico de navegación del documento. https://webaim.org/techniques/keyboard/tabindex. Se ha decidido usar un valor 0 para que se siga el 
                            orden del código fuente del documento
    - Video y audio: Se ha añadido un elemento <p> a cada uno de estos elementos para poder leer su contenido y así mejor la accesibilidad. Según el estándar de html5 se puede utilizar 
                    el elemento <figure> y dentro de este <figcaption> para encapsular al elemento video y así también mejorar la accesibilidad, pero se ha optado por la primera opción, 
                    siguiendo la recomendación que me ha dado la profesora de la asignatura. 
    - Respecto al estado del estilo en la presentación, se ha modificado ligeramente el nav, ya que tenía un atributo de estilo "position: fixed", he considerado que 
      esto dificultaba la capacidad que tenía el sitio web de que fuera completamente responsive, por lo que decidido eliminarlo y dejar un nav en la posición que le corresponde.
    - En cuanto a las etiquetas meta, inicialmente se había incluido <meta name="application-name", pero se ha decidido eliminarla ya que en https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta/name 
        recomiendan "Simple web pages shouldn't define an application-name."



