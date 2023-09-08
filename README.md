#TEST-FINAL-TRATAMIENTO-DE-DATOS

Este repositorio contiene un clasificador de tipos de carnes, el cual trabaja con un DATASET, cuyo link de descarga es el siguiente:

(https://drive.google.com/file/d/1Z5DJ-MVS1TQV1kow9mIFWTec-ZdOLRLF/view?usp=sharing)

El Archivo descargado posee una carpeta con nombre Dataset y posee dos subcarpetas: train y test.  Cada una contiene fotografias de carnes de 8 tipos clasificadas en subcarpetas.

##OBJETIVOS:

  - Obtener un clasificador de imágenes de forma que dada una nueva imagen se pueda obtener la clase correspondiente.
  - Obtener las matrices de confusión del modelo, la matriz de confusión del error en training y la de test.

##LIBRERIAS UTILIZADAS EN EL PROYECTO A SER INSTALADAS PARA SU FUNCIONAMIENTO.

  import sys
  import os
  from tensorflow.keras.preprocessing.image import ImageDataGenerator
  from tensorflow.keras.layers import Dropout, Flatten, Dense, Activation, Convolution2D, MaxPooling2D
  from tensorflow.keras import backend as K
  from tensorflow.keras import optimizers
  from tensorflow.keras.models import Sequential

##ARCHIVOS CONTENIDOS EN EL PROYECTO REALIZADO EN JUPYTER NOTEBOOK

- Entrenamiento.ipynb  (Código con la configuracion y el entrenamiento de la red neuronal CNN)
- Matriz_Datatest.ipynb  (Código que muestra la Matriz de confusion de basado en los datos para test)
- Matriz_Datatrain.ipynb  (Código que muestra la Matriz de confusion de basado en los datos para train)
- Prueba.ipynb (Código que permite probar el reconocimiento de imagenes)
- ./modelo/pesos.keras  (archivo que se genera al entrenarse la CNN)
- ./modelo/modelo.keras  (archivo que se genera al entrenarse la CNN)

