# TC3007C.502_DeepLearning
#### Manolo Ramírez Pintor - A01706155
Módulo 2 Implementación de un modelo de deep learning. (¡Con Tom y Jerry!)   

### Dataset:
El dataset que usé para este trabajo [fue el siguiente](https://www.kaggle.com/datasets/balabaskar/tom-and-jerry-image-classification). Dentro se encuentra una carpeta de imágenes de Tom y Jerry, perteneciendo a dos episodios de la serie, cuadro por cuadro.

### Video:
El video que hice se encuentra [en este link de OneDrive](https://1drv.ms/v/s!AjpnOhcgUf2f2lOd_9-A0avRMUUN?e=yEZnNY). Alternativamente, se puede descargar el repositorio y ver el video que se encuentra en la carpeta ``video``. 😄

### Descripción:
En este documento hice un modelo convolucional de varias capas y neuronas capaz de diferenciar entre Tom y Jerry, haciéndolo un clasificador binario. Para ello utilicé librerías como ``TensorFlow Keras``, ``Splitfolders``, ``Matplotlib`` y ``cv2`` para lograrlo. ¡Muchas imágenes de Google funcionan!   

Durante esta aventura me enfrenté a varios problemas y curiosidades que me permitieron conocer más cómo funciona este tipo de modelos. Estoy satisfecho con lo que hice. ¡Espero que le agrade! 😃

### Rendimiento de los modelos:
Durante la realización de este trabajo obtuve 5 modelos con los siguientes rendimientos:   
* **Modelo 1:** Accuracy: ``68.34%`` _(0.6834)_
* **Modelo 2:** Accuracy: ``73.61%`` _(0.7361)_
* **Modelo 3:** Accuracy: ``89.21%`` _(0.8921)_
* **Modelo 4:** Accuracy: ``86.54%`` _(0.8654)_
* **Modelo 5:** Accuracy: ``95.83%`` _(0.9583)_

Al intentar realizar Data Augmentation, lo hice de varias maneras, en cierto momento toqué Paint para hacer Data Augmentation de forma totalmente manual y funcionó (como eran muy pocos datos no iba a ser la gran comparación), así que concluí que TensorFlow estaba haciendo cosas extrañas con mis imágenes antes de poder entrenar y nunca tuvo sentido lo que pasó. Este es el accuracy que obtuve:   
* **Modelo 5:** ``56.25%`` _(0.5625)_

### ¿Qué contiene el repositorio?

En el documento ``model_training.ipynb`` se encuentra todo el proceso de entrenamiento que se realizó para generar los modelos de preducción.   

En el documento ``model_testing.ipynb`` se encuentra un tester de los modelos generados, dentro vienen instrucciones de uso.   

Dentro de la carpeta ``images`` se encuentran imagenes para probar los modelos generados.

Dentro de la carpeta ``models`` se encuentran los modelos que se entrenaron utilizando el dataset de imágenes anteriormente mencionado.

¡Gracias! 😀