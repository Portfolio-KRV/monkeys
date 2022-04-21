# Monkeys
Desarrollado en el curso de Redes Neuronales por: Diego Quezada y Kevin Reyes.
## Objetivos
- Aplicar redes neuronales convolucionales a la clasificación de razas de monos utilizando Transfer Learning.
- Visualizar el estado interno de la red convolucional de forma interpretable utilizando CAM.
- Comparar rendimiento de red VGG16 y VGG19.
- Comparar rendimiento de red CNN, CNN con skip connections entrenadas exclusivamente para clasificar monos con las redes con Transfer Learning.

## Descripción
Redes neuronales convolucionales para la clasificación de razas de monos, utilizando skip connections, transfer learning y método CAM para la visualización del estado interno de la red.

## Conclusiones
- Las redes neuronales con Transfer Learning tienen un rendimiento superior a las redes entrenadas exclusivamente para la clasificación de monos, ya que guardan un gran conjunto de patrones en sus parámetros, los cuales puede ser útiles para el reconocimiento de objetos en otros problemas de clasificación.
- El método CAM es una herramienta de gran utilidad para visualizar el estado interno de la red convolucional y detectar errores que la red comete al predecir de forma interpretable.
- El rostro de los monos suele ser un punto de gran atención para la red al momento de predecir la raza del mono.

## Stack de tecnologías
- Numpy.
- Pandas.
- Matplotlib.
- Seaborn.
- Cv2.
- Keras.
- Tensorflow.
- VGG16.
- VGG19.