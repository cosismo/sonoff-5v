# Información Técnica Sonoff 5V

Bienvenido al Internet de las Cosas.

Para comenzar a utilizar tu switch wifi Sonoff 5V y encontrar toda la información técnica, te recomendamos las siguientes ligas:

### Aplicación para control:
* Android: [https://play.google.com/store/apps/details?id=com.coolkit&hl=en](https://play.google.com/store/apps/details?id=com.coolkit&hl=en)
* IOS: [https://itunes.apple.com/us/app/ewelink/id1035163158?mt=8](https://itunes.apple.com/us/app/ewelink/id1035163158?mt=8)

### Guía rápida en Español sobre cómo conectar el Sonoff (documento PDF):
[https://drive.google.com/file/d/13ULx0XDxDTZj_m6TrO3Xd_3ScrNewz3U/view?usp=sharing](https://drive.google.com/file/d/13ULx0XDxDTZj_m6TrO3Xd_3ScrNewz3U/view?usp=sharing)

### Guía completa en inglés:
[http://ewelink.coolkit.cc/?p=143](http://ewelink.coolkit.cc/?p=143)


### Videos de configuración: 
* Instalar app IOS Español: [https://www.youtube.com/watch?v=ktxUtZRa0t8 ](https://www.youtube.com/watch?v=ktxUtZRa0t8)
* Dar de alta Android Español: [https://www.youtube.com/watch?v=lnpzx9SlGR0](https://www.youtube.com/watch?v=lnpzx9SlGR0)

### Instrucciones de la página oficial de la aplicación (inglés):
[https://www.itead.cc/wiki/EWeLink_Introduction](https://www.itead.cc/wiki/EWeLink_Introduction)

### Instrucciones de la página oficial para hacer funcionar Sonoff con Amazon Alexa (inglés):
[https://www.itead.cc/blog/ewelink-works-with-alexa-tutorial#tutorial](https://www.itead.cc/blog/ewelink-works-with-alexa-tutorial#tutorial)

### Instrucciones de la página oficial para hacer funcionar Sonoff con Google Home (inglés): 
[https://www.itead.cc/blog/sonoff-work-with-google-home](https://www.itead.cc/blog/sonoff-work-with-google-home)

### ¿Qué hacer si la App no puede detectar el dispositivo después de los 3 minutos que indica el manual?
Por diversas razones de compatibilidad (el módem, el smartphone, el firmware, el sistema operativo) en algunas ocasiones no es posible configurar de la manera "normal" (Quick pairing Mode), pues la App se queda buscando el dispositivo y nunca lo encuentra. 

En este caso la solución es usar el modo de emparejamiento compatible (Compatible Pairing Mode AP) que convierte al sonoff en un Access Point inalámbrico y te permite configurarlo sin necesidad de tu módem WiFi. 

En el modo de apareamiento compatibible, al que llegas presionando dos veces durante aproximadamente 7 segundos el botón de apareamiento (ver video al final de este párrafo), te aparecerá una red inalámbrica ITEAD-****** con un password 12345678 Conéctate a ella y después regresas a la App (sin desconectarte de la red ITEAD-******) y podrás configurar el Sonoff presionando el botón de modo de apareamiento compatible (Compatible Pairing Mode).

Aquí un video de cómo parpadea el LED cuando se presiona la primera y la segunda vez (se muestra un sonoff basic, pero el funcionamiento en el Sonoff 5v es el mismo):
[https://www.youtube.com/watch?v=iCRq5obr_SE]

Las instrucciones completas de este modo están en el manual (inglés) en el punto 3.2.b Compatible Pairing Mode.
[http://ewelink.coolkit.cc/?p=143]

¡Suerte! 

   Equipo Cosismo

# Notas Importantes para la instalación eléctrica:
  1. Te sugerimos ampliamente que la instalación física sea realizada por un profesional. Si tienes conocimientos eléctricos y decides hacerlo por ti mismo, te recomendamos que leas muy bien las instrucciones del PDF anexo y tomes todas las precauciones para evitar dañar el dispositivo y/o tu instalación eléctrica.

  2. ESTE DISPOSITIVO DEBE ALIMENTARSE CON 5V. SI LO ALIMENTAS CON OTRO VOLTAJE SE DAÑARÁ IRREVERSIBLEMENTE. Usa un cargador microUSB 5v 2A para alimentarlo. A la salida sí puedes conectar cualquier voltaje entre 0-220V porque es un contacto «seco», totalmente aisaldo de la alimentación de entrada. **El problema más común de este dispositivo tiene como síntoma que el switch se prende y se apaga por sí mismo, y es causado por una fuente o cable de alimentación de menos capacidad que los 2A. Usa una fuente con la capacidad correcta y de buena calidad para evitar este problema.**
  
3. Verifica muy bien que utilices los contactos de salida COM y NO (normalmente abierto) para la salida. El contacto NC (normalmente cerrado) generalmente no se usa. 
  
4. Si vas a usar este dispositivo en modo pulso, asegúrate que esté configurado de esa manera, si conectas una cerradura o una puerta eléctrica en modo contínuo o self-locked, puede sdañar la cerradura, puerta o el dispositvo irreversiblemente. Para más detalles revisa el PDF anexo con la guía de instalación básica.
  
5. La carga máxima que soporta es de 10A (alrededor de 1000w.
  
6. El dispositivo tiene garantía contra defectos de fábrica, físicos (roturas, partes incompletas, etc.), no contra daño eléctrico causado por una mala instalación.
