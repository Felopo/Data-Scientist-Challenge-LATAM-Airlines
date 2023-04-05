# Data-Scientist-Challenge-LATAM-Airlines
Proyecto donde se desarrolla el desafío planteado por LATAM.

## Descripción del problema: 
El problema consiste en predecir la probabilidad de atraso en los vuelos que despegan o aterrizan en el aeropuerto de Santiago De Chile (SCL). Para resolverlo se utilizará una base que contiene los vuelos que despegaron o aterrizaron en el aeropuerto de SCL en el año 2017.

## Consideraciones adicionales:
- No se consideraron variables exógenas por tema de tiempo, pero creo que la distancia entre la ciudad de origen y la de destino, además de las condiciones climáticas serían un buen factor para agregar al modelo.

- Considerando el Git-flow, se creó una rama "development" en la cual se iba trabajando y agregando nuevas funcionalidades a medida que estaban listas. La rama "main" solamente fue tocada cuando las funcionalidades estaban listas y revisadas.

- Como se comenta en el notebook, los vuelos que despegaron antes del horario programado se les dejó con 0 minutos en la variable "min_diff", pues la naturaleza de la variable mide retraso, y estos casos no corresponden a retrasos.

- Para la actividad 2.) el archivo csv pedido se encuentra en la siguiente ruta: `data/output`
