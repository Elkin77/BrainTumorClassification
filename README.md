# BrainTumorClassification

En el siguiente artı́culo, se construirán dos
modelos basados en redes neuronales para el proce-
samiento de imágenes y la clasificación de tumores
cerebrales utilizando el dataset de Kaggle (Brain Tumor
Classification (MRI)), con el fin de poner en práctica los
conceptos de deep learning y de manera experimental
comprobar la relación que existe entre definir una buena
arquitectura de red neuronal, la normalización de los
datos y el ajuste de hiperparámetros, ası́ como definir el
número de iteraciones (Épocas) y una función de pérdida
y ajuste de pesos adecuada para variar el modelo y
tender a un buen desempeño. Para ello se inicia con
la construcción de una red neuronal feed fordward de
pocas capas y se realiza el entrenamiento modificando
la cantidad de épocas e hiperparámetros, posterior a
ello se construye un modelo convolucional con varias
capas ocultas y filtros sobre la imagen, se aplicarán capas
de Max pooling y flattening para manejar el filtrado y
aplanamiento de las imágenes y de esta manera extraer
más caracterı́sticas en un vector resultante. Finalmente,
se comparan los resultados de los modelos en la va-
riación de épocas y ajuste de parámetros y se grafica
el desempeño y la función de pérdida a lo largo de
cada iteración. Determinando que este problema de depp
learning se puede resolver con una red neuronal con
pocas capas ocultas, pero con una mejor distribución del
dataset y un manejo categórico de las etiquetas haciendo
uso de one-hot encoding. De igual manera, se determina
que es necesario agregar varias capas dropout para la
regularización y evitar el sobre ajuste (overfitting) y
aumentar la cantidad de epocas para tener un mejor
desempeño y disminuir el error.
