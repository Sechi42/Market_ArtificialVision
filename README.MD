## Descripción del Proyecto

A la cadena de supermercados Good Seed le gustaría explorar si la ciencia de los datos puede ayudarle a cumplir con las leyes sobre el alcohol, al asegurarse de no vender alcohol a personas menores de edad. Te piden que hagas esa evaluación, así que, cuando te pongas a trabajar, ten en cuenta lo siguiente:

- Las tiendas están equipadas con cámaras en el área de pago, las cuales se activan cuando una persona está comprando alcohol.
- Los métodos de visión artificial se pueden usar para determinar la edad de una persona a partir de una foto.

La tarea, entonces, es construir y evaluar un modelo para verificar la edad de las personas. Para empezar a trabajar en la tarea, tendrás un conjunto de fotografías de personas que indican su edad.

## Instrucciones del Proyecto

1. Pasa un cuestionario para verificar tu comprensión de la descripción del proyecto.
2. Realización de un análisis exploratorio de datos para obtener una impresión general del conjunto de datos.
3. Entrenamiento y evalúación el modelo.
4. Combinación de el código, salida .
5. Conclusiones de la evaluación del modelo.

## Conclusiones

En este proyecto se realizaron diversos analisis a los cuales se llegaron a los siguientes puntos:

- Los datos tienen un intervalo de foftgrafias con personas de 1 año hasta 100 años de edad
- La media de edad de las personas en las fotografías es de 31 años y el 75% tiene menos de 41 años, por lo que el modelo podría predecir mejor en rangos de 14-41 años 
- En cuanto a las metricas del modelo, el error absoluto medio es de 5.8151, considerando la desviación estandar de las edades es de 17 años, podíamos considerarlo bastante aceptable.
- Es de observar que en la epoca 8 y 18 hay un aumento del error absoluto, esto podría ser indicativo de un modelo sobreentrenado

Como conclusión obtenemos un modelo que tiene una predictivilad de una fiabilidad interesante, habría que estudiar más parametros para moder obtener unos resultados superiores. 





