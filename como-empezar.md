# Cómo empezar con Flexbox

Para entender bien este modelo de layout \(diseño\) debemos entender algunos conceptos básicos.

Primero la disposición _flex_ debe estar constituido por elementos padres e hijos, el padre será el contenedor Flexible “_flex container_” y los serán los elementos Flexibles “_flex item_”.

![](https://lh4.googleusercontent.com/8jJLISAPh1qHwvDtIXkDlsCuP-xtM-XcNqUkhMP-qHI5yc29qPmhHscTP3OJlMtuIEKDiLQxlSrMp6ejwbmCGa3KMPaDD5UCztC0qA5RyysF2QWgKYNBJTkbRO8UbusKSXbwM7ia)![](https://lh3.googleusercontent.com/VKnbMkFEF8tUszeBND9JBo2IAcPSRH3IzL9zjUSAie7Ru80E96lvPEiNgdSJEnB0xTV_wSC8jKOnsj_I675bzDSooghKmAhDTDQFhW4DzTAOfNetJ5uY5gG_iHsYIGors4gjHQb_)

Para comenzar a utilizar el modelo Flexbox lo primero que debemos hacer es establecer la propiedad _display_ con los valores _flex_ o _inline-flex_ en el elemento o padre. Esto lo convertirá  en el “_flex-container_”.

* **flex:** Hace que el elemento HTML sea un bloque. Los elementos del bloque generalmente comienzan una nueva línea y los elementos hermanos aparecen en diferentes líneas.
* **inline-flex**: Hace que el elemento HTML sea un elemento en línea. Los elementos en línea no inician una nueva línea y sus hermanos pueden aparecer en la misma línea, pues estos ocupan solo el tamaño de su contenido.

El conjunto de propiedades que nos presenta la especificación CSS3 en cuanto al módulo Flexbox, las podemos dividir en dos grupos; las propiedades para el contenedor y las propiedades para los items.  


