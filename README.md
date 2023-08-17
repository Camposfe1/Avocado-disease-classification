# Avocado-disease-classification
Código utilizado para la evaluación de diferentes modelos de Machine learning, a partir de datos de imágenes digitales de aguacates

Los Códigos que se encuentran corresponden a los utilizados en mi tesis de maestría: <b>TÉCNICAS DE INTELIGENCIA ARTIFICIAL PARA CLASIFICACIÓN Y DETECCIÓN DE PROBLEMAS FITOSANITARIOS EN FRUTOS DE AGUACATE (<i>Persea americana</i> Miller).</b>

El trabajo se conforma de dos capítulos:

1. IDENTIFICACIÓN AUTOMÁTICA DE ENFERMEDADES EN FRUTOS DE AGUACATE CON BASE EN MÁQUINAS DE APRENDIZAJE Y DESCRIPTORES CROMÁTICOS
2. ARQUITECTURAS CNN PARA LA DETECCIÓN Y CLASIFICACIÓN DE ENFERMEDADES EN FRUTOS DE AGUACATE

Para el capítulo 1 se utilizaron algoritmos de <i>Machine learning</i> como ```Random Forest, Support Vector Machine y Multilayer Perceptron```, para la clasificación e identificación de tres clases objetivo correspondiente a imágenes digitales de frutos de aguacate. El conjunto de datos se encuentra en este [enlace](https://www.kaggle.com/datasets/camposfe1/deteccin-de-enfermedades-con-machine-learning). Por otra parte, se encuentran los modelos optimizados ```.pkl``` para su utilización.

Los archivos utilizados para este capítulo tienen una numeración del <u>1 - 6</u>.

En el capítulo 2 se utilizaron algoritmos de <i>Deep learning</i> como ```Convolutional Neural Networks```, además su implementación con modelos de aprendizaje automático, teniendo modelos híbridos; todo esto para la clasificación de imágenes digitales de enfermedades en frutos de aguacate. En este caso se utilizaron 669 imágenes originales para el entrenamiento de las redes, y se encuentran en este [enlace para descarga](https://www.kaggle.com/datasets/camposfe1/deteccin-de-enfermedades-con-machine-learning).

En este caso, los archivos consisten de la siguiente forma:

a) Los archivos que inician con A1, A2, A3 y A4; son los modelos CNN entrenados.
b) Los archivos que inician con HM, corresponden a los modelos híbridos.
