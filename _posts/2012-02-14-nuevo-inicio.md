---
layout: post
title: "Nuevo inicio"
category: general
tags: []
---
{% include JB/setup %}

Si has estado leyendo esta página desde hace mucho, o entrado de casualidad para ver algún nuevo 
taller o charla, puedes comprobar que hay un cambio total en nuestro sitio.
Esto no es sólo un nuevo diseño, sino una reescritura completa del software de blog que utilizamos.
El antiguo sitio funcionaba en un servidor en Godaddy con [Wordpress](http://wordpress.org/).

Ahora bien, este sitio es sólo un montón de archivos HTML estáticos que se generan con 
[Jekyll](http://jekyllrb.com/), un generador de sitios estáticos escrito en **Ruby**,
ejecutándose en [Github](http://github.com/). 
Esto ha mejorado la velocidad del sitio y nos permitirá escribir más a menudo, o al menos eso esperamos.

Entonces, ¿qué beneficio real me dan? Pues ninguno, a menos que desees participar con algún artículo,
pues contáctanos para ello, ¡eres bienvenido!. Bueno, por mi parte, puedo escribir todo lo que quiero
en formato [Markdown](http://daringfireball.net/projects/markdown/) sin tener que preocuparme que 
el puerco del editor no edite el formato de mis artículos. Además, tengo absoluto control sobre 
el estilo y el diseño de la página.

####<abbr title="Too long; didn't read">TL;DR</abbr>####

### Motivos

Los motivos que me han llevado a migrar el sitio a Jekyll son dos: velocidad y sencillez.
Al ser contenido estático, pierdes algunas cosas como el sistema de comentarios, pero ya está
resuelto con el uso de [Disqus](http://disqus.com/). De paso he aprovechado para hacer un pequeño 
nuevo diseño.


### Markdown y la bondades de SASS

La creación de artículos o posts utilizando solamente etiquetas HTML puede llevar mucho tiempo, como
estar propenso a errores con el uso del editores WYSIWYG cómo el de Wordpress.
Ahora utilizamos Markdown, un lenguaje de marcado ligero, que convierte de foma automática y 
segura nuestros textos a HTML. Además, utilizamos SASS para simplificar drásticamente nuestro código CSS.

### No hay Administrador (back-end)

La mejor parte de **Markdown** es que convierte todo en archivos HTML estáticos. Por lo tanto,
no hay ningún administrador visual en el sitio.

Desde ahora, nos olvidamos por completo de actualizaciones engorrosas y parches a wordpress
o a ningún otro software debido a posibles ataques, del molesto spam, y demás mierdillas.

Esto significa, que no es posble la inactividad del sitio debido a una falla en la base de datos.
También es mucho más difícil atacar el sitio. El único punto de ataque es ahora el servidor web,
y bueno siempre va a existir ¿no?. Sólo nos preocupamos por el contenido.
 
### Despliegue automático

> git push

Eso es todo lo que tengo que hacer para publicar el nuevo contenido.

### Software de control de versiones

Como desarrollador, estoy acostumbrado a los sistemas de control de versiones como Git y Mercurial.
(Lo adminto, use CVS y SVN. Y sí, ¬¬ soy de la vieja escuela).
Todos estos programas llevan el historial de cada acción en el repositorio, lugar en donde se almacena 
todo el código fuente. Ahora ya saben por si meten la pata, esto se resolvería sin nigún problema en un ¡Achís!.

Dado que los archivos de Markdown son sólo eso, archivos. Incluso ahora puedo hacer diferencias entre 
estos (diff), crear ramas (branch), fusiones (merge), incluso cherry pickings con toda libertad.

Uno no puede pensar en hacer estas cosas en Wordpress, sobre todo, sin hacer alguna modificación 
importante en el software.

Por útlimo, si estás interesado en revisar y contribuir en el sitio, estoy almacenando todo el 
sitio en un proyecto en [github](https://github.com/idatux/idatux.github.com). Y sí, eres bievenido
ayudar en el sitio.
