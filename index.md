---
layout: page
show_title: false
banner:
  collection: america
  pid: PhilipsGalle
  y: 25%
  clickable: yes
  height: '500px'
---

Esta es una colección de juegos autojugados. Estos son juegos de simulación en los que partes importantes de la jugabilidad se delegan a la máquina o que simplemente son jugados enteramente por esta. Este tipo de juegos tienen sus inicios en 1970, cuando John Conway propuso su modelo de autómatas celulares llamado Game of Life. En Game of Life, establecemos los parámetros iniciales de la simulación y luego esta funciona por su propia cuenta, potencialmente de manera infinita. Los juegos autojugados siguen este espíritu y se juegan de manera automatizada.

### Construcción de los metadatos
Los metadatos de la colección se construyeron siguiendo el siguiente protocolo:

-desarrollador: la persona, empresa o institución que desarrolló el videojuego. Descrita con nombre y apellido, o nombre de la empresa/institución. Las iniciales de cada palabra deben ir en mayúscula, excepto si se trata de una empresa (dato categórico).

-fecha: fecha de lanzamiento del juego. Descrita solamente con el año (dato numérico).

-plataforma: sistema en el que funciona el videojuego. Descrito con el nombre del sistema (dato categórico).

-motor de juego: entorno de desarrollo que proporciona herramientas para la creación del videojuego. Descrito con el nombre del motor de juego (dato categórico). 


Plantilla para colecciones en Wax: [Documentación](https://minicomp.github.io/wiki/#/wax/).

Las imágenes usadas en esta pltanilla son de Dominio Público y provienen del archivo digital del [RijksMuseum](https://www.rijksmuseum.nl/nl)

### Busca la colección

#### Por desarrollador
{% include collection_gallery.html facet_by='desarrollador' collection='america' %}

#### Por plataforma
{% include collection_gallery.html facet_by='plataforma' collection='america' %}