# MachineLearningAplicado
Asignatura Computación Científica y Analítica | Rolando García M - Rabih Souiden M

1. Del script de forest fires:
a. ¿Se desea resolver el problema utilizando aprendizaje supervisado o no
supervisado? ¿Es un problema de clasificación o de regresión?

El problema se intenta resolver por medio de un algoritmo supervisado y pertenece a un problema de regresión.

b. ¿Qué interpretación le puede dar a los resultados obtenidos?

El algoritmo mantienen una precisión del 89% sobre los resultados.

2. Del script de recursos humanos (rrhh):
a. ¿Cuál es la clase para la que el modelo más se equivoca? ¿Por qué?

La clase de salarios "Low" sobre la matriz de confusión puede verse como varian las predicciones con las demás clases.

b. ¿Cuál cree que es el propósito del parámetro max_depth usado al
momento de instanciar el modelo de árbol de decisión?

El parámetro max_depth corresponde a la profundad máxima para los nodos del árbol de decisiones.

c. Para este caso particular, ¿por qué cree que es difícil obtener un buen
clasificador?

Existen pocos atributos para el problema y algunos llegan a ser irrelevantes.

3. Identificación de géneros musicales: Tenga en cuenta que hay dos scripts:
music.ipynb y music-multiclass.ipynb. En el primero se intenta crear un modelo
clasificador solo para dos clases (caso binario) y en el segundo se entrena uno
para todas las clases (géneros musicales) del dataset.

a. Para el caso binario (jazz and blues vs. soul and reggae) ¿Es posible
obtener mejores métricas entrenando un modelo basado en Random
Forest?


b. Escoja otro par de géneros, entrene un conjunto de modelos y documente
los resultados del mejor que se haya obtenido.


c. Para el caso multi-clase, ¿cuál es la clase para la que el modelo más se
equivoca? ¿Por qué?


d. Para el caso multi-clase, el modelo basado en red neuronal parece estar
mayoritariamente sesgado hacia un género particular ¿Cuál género cree
que es?

4. Segmentación de cajas de compensación familiar (subsidio):
a. ¿Qué cajas de compensación parecen ser mayoritariamente diferentes a
las demás?
b. ¿A partir de qué características utilizadas para el entrenamiento del
modelo se podría explicar la razón por la que las cajas anteriores fueron
agrupadas en clusters tan pequeños?
c. ¿Se pueden obtener resultados más homogéneos utilizando cantidades
diferentes de clusters para el entrenamiento? Entienda homogeneidad
como clusters con cantidades similares de instancias de datos.
