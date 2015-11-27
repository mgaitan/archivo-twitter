Archivo de Twitter
-------------------

Un repositorio histórico de los twitts de algunos políticos y personalidades públicas de la Argentina.
Se actualiza periódicamente.



Utiliza la herramienta `twitter-archiver` que se incluye en la biblioteca [Twitter](https://pypi.python.org/pypi/twitter) para Python.


El límite impuesto por la API de Twitter es de 3200 twitts que se relevaron por primera vez el 27 de noviembre de 2015.
Esto hace que no haya registro de tuits de varios años atrás para aquellas cuentas que *tuitean* mucho.

Cómo ver el tuit original
---------------------------

El formato de los archivos

```
ID FECHA AUTOR CONTENIDO
```

Y el link permanente de un tuit es `https://twitter.com/<AUTOR>/status/<ID>


Por ejemplo, el tuit archivado

```
668515322840924160 2015-11-22 16:44:08 ART <CFKArgentina> El futuro va a ser el que quieran los argentinos y el que definan los argentinos con memoria y con la certeza de que nada es para siempre
```

corresponde a https://twitter.com/CFKArgentina/status/668515322840924160


Contribuí
---------

- ¿Tenés tu propio archivo y te gustaría integrarlo? proponé un Pull Request.
- ¿Te parece que falta una cuenta relevante? Editá `update.sh` y proponé un Pull Request.





