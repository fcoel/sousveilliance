# hackaton-boletin-oficial

Archivos desarrollados durante el hackarton de boletin oficial

Dos equipos de trabajo
- Descarga de PDF y datos -> descargas
- Procesamiento de datos -> parseo


Programadores que participaron del evento:
@javierjlujan
@diegodlh
@martinszy
@fnbellomo
@pablosoffietti.

## Descargar los datos

Es necesario descargar los datos igj para realizar varios de los análisis del repo. Para esto:

    $ python3 getData.py

Y listo!

## comparar/comparador.py
Queríamos saber si las sociedades que figuran en el Boletín Oficial efectivamente
figuran en la base de datos de la IGJ también.
El script comparador.py toma una a una las sociedades mencionadas en los
Boletines Oficiales descargados (en principio sólo las Sociedades Anónimas
constituidas) y verifica su existencia en la última base de datos de IGJ
descagada.
Encontramos sociedades en el Boletín Oficial que no se encuentran en IGJ.
Suponiendo que podía deberse a que la información en IGJ no está del todo
actualizada, queremos intentar nuevamente con Boletines Oficiales más antiguos
(anteriores al 30jun16). Esto está pendiente (hay que descargar estos Boletines
Oficiales).
delahera@gmail.com

