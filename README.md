Sensorino - Iniciandote con Componentes de Montaje Superficial
================================================================

Sensorino es una tableta electrónica programable compatible con
Arduino Leonardo impulsada por la comunidad OpenHardware.SV diseñada
en colaboración por TeUbi.co y ALSW para enseñar los fundamentos
básicos sobre el diseño de tabletas electrónicas haciendo uso de
componentes de montaje superficial.

La tableta es basada en el microcontrolador ATMega32u4 y contiene
el bootloader de Leonardo, pero además incluye sensores y LEDs
indicadores por lo que no requiere de componentes externos más que
una fuente de alimentación una vez programada.

Actualmente la tableta tiene la posibilidad de armarse utilizando el
sensor de gestos APDS-9960 o el inclinómetro sencillo RPI-1031. Estos
sensores permiten implementar aplicaciones muy sencillas que pueden
fácilmente ser demostradas con LEDs incluídos.

Al estar basada en Leonardo la tableta también permite utilizarse como
dispositivo de entrada (teclado o mouse) con lo que se le pueden dar
aplicaciones sumamente interesantes de interacción con computador.

Esta es una tableta didáctica diseñada con la idea de aprender las bases
del diseño utilizando componentes de montaje superficial por lo que se
incluye el mismo diseño eléctrico y de PCB en distintas etapas del
diseño que facilitan y sirven como guía de los productos esperados.


Últimas adiciones
=================

+ Agregado esquemá eléctrico

Costo/Lista de Materiales
=========================

Revisar archivo adjunto BOM.csv.

Pre-requisitos/Requerimientos
=============================

En función del diseño que quieras modificar puedes encontrar las fuentes
en distintas etapas. Sin embargo para seguir todo el proceso desde cero
necesitas cumplir los siguientes requerimientos:

Software:

* EAGLE Layout editor.
* IDE Arduino.
* GIT (para guardar tus avances)

Herramientas requeridas:

* Pistola de calor de temperatura y flujo regulable (Se recomienda Sparkfun 303D)
* Tercera mano
* Pinza curvada auto-blocante anti-estática
* Espátula plástica o tarjeta de vinil (para aplicar la pasta)
* Pasta para soldar libre de plomo


Construcción y uso
==================

Revisar directorio "Documentación"

Carpetas
========
* *doc*: Utiliza esta carpeta para ingresar toda la documentación que consideres
necesaria para tu proyecto. De preferencia utiliza formatos libres como "ODF"
o simples archivos de texto, si puedes crear una página web en HTML recuerda
renombrar el archivo principal como "index.html" para que pueda ser accedido
fácilmente en caso de que alguien copie esta carpeta en un servidor web.
* *src*: Coloca en esta carpeta todos los archivos de código fuente del software
de control de tu proyecto Open Hardware. Si utilizas un IDE como Eclipse o Arduino
copia dentro de src la carpeta del proyecto.
* *dsn* / *diseño*: En esta carpeta coloca todos los archivos para el diseño de tu
proyecto.
  +  *main*: Coloca en esta carpeta los archivos de diseño original que pueden
incluir, pero no limitarse a: Dibujos 2D, diseños 3D, archivos CAD, bibliotecas
de componentes, dibujos técnicos adicionales.
  +  *aux*: Coloca en esta carpeta los archivos de diseño auxiliares que ayuden
a construir tu proyecto. Los archivos de diseño secundario pueden incluír diseños
2D o 3D en formato de intercambio, dibujos técnicos adicionales, formatos listos
para manufactura, artes gráficos adicionales.
* *extra*: Esta carpeta es libre, aquí puedes colocar otros archivos que se
puedan requerir para hacer funcionar o construir tu proyecto. Un ejemplo de ello
puede ser un driver controlador de un dispositivo específico o vínculos a software
relevante, fotografías o videos.

Excepción de responsabilidades
==============================

Es recomendable que incluyas un texto como el siguiente en tus proyectos:

> El presente proyecto se comparte "tal cual" con el único objetivo de que sea útil.
El/los creadores del presente hardware y su software asociado no pueden garantizar su
correcto funcionamiento bajo ninguna circunstancia. El/Los autor/es de este proyecto
no podrá/n hacerse responsable/s de cualquier pérdida de carácter material, personal o
económico a su persona o terceros derivados de la utilización del mismo. Este proyecto
no deberá ser utilizado bajo ninguna circustancia en sistemas de carácter crítico
o sistemas de los cuales dependan vidas de personas de manera directa o indirecta.


Licenciamiento
==============

Agrega aquí la licencia que utilizas en el código fuente de tu proyecto, adicionalmente
agradeceríamos si colocas la nota de atribución de la plantilla al final.

> La plantilla de este README.md ha sido desarrollada por la comunidad openhardware.sv
con el objetivo de facilitar la documentación de proyectos. Esta plantilla está protegida
bajo la licencia CC BY, puedes modificarla y redistribuirla manteniendo esta nota de
