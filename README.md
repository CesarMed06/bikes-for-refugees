# Bikes for Refugees Scotland

Replica de la web de Bikes for Refugees Scotland (https://www.bikesforrefugees.scot/).

## Objetivo del proyecto

El ejercicio consiste en replicar visualmente una captura de pantalla de la web original usando solo HTML y CSS, sin frameworks. El resultado tiene que ser fiel al diseño original en cuanto a layout, colores, tipografía y comportamiento de los elementos.

## Cómo lo he hecho

Empecé por la estructura HTML con etiquetas semánticas y a partir de ahí fui añadiendo los estilos. Para el layout usé Flexbox tanto en la barra de navegación como en la disposición general de la página (columna de contenido + sidebar). Las imágenes las subí a Cloudinary y las referencié desde ahí en lugar de tenerlas en local.

También añadí mejoras de accesibilidad como un skip link, atributos aria-label en los enlaces y botones, y roles semánticos para que la estructura sea legible por lectores de pantalla.

## Dificultades

Lo que más me costó fue ajustar las imágenes del sidebar, ya que cada una tiene proporciones distintas y había que combinar object-fit y object-position para que encajaran bien sin distorsionarse. También tuve que repasar cómo funciona el border-bottom del heading de sección para que la línea naranja solo cubra el texto y no todo el ancho.