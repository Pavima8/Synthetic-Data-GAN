# Generación de Imágenes Sintéticas a partir de CIFAR100 usando GANs
Este proyecto utiliza Redes Generativas Adversarias (GANs) para generar imágenes sintéticas a partir del conjunto de datos CIFAR100. CIFAR100 es un conjunto de datos ampliamente utilizado en el campo de la visión por computadora y el aprendizaje profundo, que consta de 100 clases diferentes de imágenes, cada una con 600 imágenes de tamaño 32x32 píxeles en color.

## Objetivo
El objetivo principal de este proyecto es entrenar un modelo GAN capaz de generar imágenes sintéticas que se asemejen a las imágenes reales del conjunto de datos CIFAR100. Esto implica entrenar una red generadora para que produzca imágenes realistas que sean indistinguibles de las imágenes reales para un observador humano, mientras que una red discriminadora debe aprender a distinguir entre las imágenes generadas y las reales.

## Tecnologías Utilizadas
Python: Lenguaje de programación principal.
TensorFlow/Keras: Librerías de aprendizaje profundo para la implementación de modelos GAN.
NumPy: Biblioteca para operaciones matemáticas.
Matplotlib: Biblioteca para visualización de datos.

## Conclusiones
este estudio subraya la influencia significativa de la arquitectura del modelo en el rendimiento de las Redes Generativas Adversariales. Se encontró que la introducción de capas convolucionales mejora notablemente la capacidad del modelo para aprender características de alto nivel y generar imágenes más detalladas y realistas. Aunque se necesitan más investigaciones para comprender completamente el impacto de la reducción de parámetros en los modelos GAN, estos resultados ofrecen perspectivas valiosas para el desarrollo futuro de técnicas de generación de imágenes más efectivas y eficientes.
