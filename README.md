# Objetivo
 - Desarrollo de un algoritmo genético para optimizar problemas en los que el objetivo sea conseguir una red neuronal correctamente entrenada para resolver un problema, sin usar los mecanismos de entrenamiento basados en técnicas de descenso de gradiente.
 - La red debe clasificar iris de varias plantas.
 - Los datos de entrada son el ancho del sépalo, el alto del sépalo, el ancho del pétalo y el alto del pétalo.
 - La salida es un único dato que define el tipo de iris (iris-setosa, iris-versicolor, iris-virginica).
 - El dataset ha sido extraído de: https://archive.ics.uci.edu/ml/datasets/iris

# Procedimientos
 - Diseño y contrucción de un MLP con una única capa oculta en un notebook externo.
 - La matriz e pesos obtenida se guarda en un archivo que más adelante se utilizará en el algoritmo genético.
 - Cada cromosoma codificará una matriz de pesos para el MLP que has programado antes. Cada gen representa un peso de esa matriz.
 - La longitud del cromosoma será la del número de pesos que necesita la red.
 - Cada gen será un número real positivo o negativo entre (-1) y (+1).
 - Se crean dos notebook diferentes con dos algoritmos genéticos diferentes, uno que implementa mutaciones y elitismo y otro más simple que no lo implementa.