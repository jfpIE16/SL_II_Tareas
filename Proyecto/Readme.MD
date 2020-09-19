# Proyecto final
## Statistical learning II
---
**José Fernando Pérez Pérez**  
josefernando.perez@galileo.edu  
20000756

## Parte 1: Detección de pacientes con enfermedades del corazón utilizando MLP
Mi propuesta de proyecto es utilizar el data set **Hearth Disease Data Set** para resolver el problema de clasificación binaria que permita interpretar los datos con información del paciente e indicar si existe o no una enfermedad del corazón.  
**Solución:** [MLP - Hearth disease](mlp-hearth-disease-classification/MLP_20000756.ipynb)

## Parte 2: Clasificación de Pokemones utilizando CNN
Como propuesta de proyecto utilizando redes neuronales convolucionales se implementará un modelo que permita la clasificación de 6 pokemones elegidos de la primera generación. El conjunto de datos se obtuvo de dos fuentes, la primera un script desarrollado personalmente que realiza búsquedas en google images con el nombre del pokemon y descarga las primeras 50 imagenes y las almacena en una carpeta con el número del pokemon; luego se realizó un proceso de limpieza manual para descartar aquellas imagenes que no eran aptas para la tarea.  
**Solución:** [CNN - Pokedex](convnet-pokedex/CNN_20000756.ipynb)

## Parte 3: Clasificación de Pokemones utilizando CNN
Propuesta, el conjunto de datos utilizados contiene la información de un mes x con una granularidad de 15 mins para cada observación se tiene el throughput total de la red 3G y LTE en ese tiempo. Se propone construir una red neuronal recurrente del tipo LSTM (Long short-term memory) para que dada una secuencia definida del throughput en un período de tiempo se pueda predecir la secuencia siguiente. Se puede aplicar para detectar anomalías en la red de tráfico.  
**Solución:** [LSTM - Throughput](lstm-throughput/LSTM_20000756.ipynb)
