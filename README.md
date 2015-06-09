# Datasets
Datasets para usar en el Fujitsu-UGR Hackathon

- El fichero *raw[csv,json,xml]* contiene los datos de una semana. 
- El fichero *raw_ampliado.csv* contiene información extra (fabricantes)
- La carpeta *ejemplos* contiene el fichero de ejemplo de uso *analizador.r*: ejemplo de como cargar un fichero y representa los datos. Hace interpolación lineal para predecir.
- La carpeta *trazas* contiene ficheros de trazas entre nodos con distintas ventanas de tiempo, habiendo sido generados a partir de los ficheros raw. Ejemplo: trazas_15m incluye para cada pareja de nodos cuantos dispositivos han sido encontrados en distintos periodos de tiempo de 15 minutos y el tiempo medio entre esos nodos.
