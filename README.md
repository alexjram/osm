# Instrucciones de uso
Para poder usarlo primero debes asegurarte de tener una buena configuración a Internet

Luego descargar unos de los archivos osm.pbf que se encuentra en esta página http://download.geofabrik.de/index.html y colocarlos en la carpeta info, y luego proceder a copiar el nombre del archivo en las lineas 8 y 18 del archivo docker-compose.yml

Una vez hecho esto ejecutar `docker compose up` este proceso va a tardar un rato

Una vez termine ejecutar ir al archivo docker-compose.yml 

 1. Comentar la línea 12
 2. Descomentar la línea 13
 3. Descomentar el bloque que va desde la línea 14 hasta la 23

Ejecutar `docker compose up` de nuevo y esperar a que se termine de ejecutar, este proceso tarda un rato especialmente si el archivo osm es grande

Al final puedes abrir el archivo index.html para ver un ejemplo de funcionamiento cargando el mapa que se importo y las localizaciones que se encuentran en ese mismo archivo

## Recomendaciones
- Para pruebas solo usar archivos de paises, mientras más pequeños más rápido es el proceso de instalación y menos recursos va a requerir
- Si es posible probarlo en un ordenador aparte al de trabajo ya que esto va a requerir una buena cantidad de recursos y así se evita detener el trabajo mientras se ejecuta la instalación
