# Descripcion del proyecto
En este repositorio se encuentra la entrega del proyecto final del curso de programacion.

Fue desarrollado por Samuel Mercado y Martin Perez.

El proyecto consistio en el entranamiento de dos modelos de aprendizaje automatico para clasificar un conjunto de personas en pacientes sanos (sin epilepsia ) y enfermos (con epilepsia) de acuerdo con una señal de electroencafalograma de cada uno de ellos.Para ello se creo un flujo de trabajo que inicio con la exploracion de los datos para analizar su estructura y las posibles complicaciones que podrian surgir de la naturaleza de estos.
 
Luego se procedio con el procesado de estos para que fueran utiles para entrenar los modelos.

Y por ultimo el entrenamiento de los modelos, haciendo uso de algoritmos para ajustar los hiperparametros y poder encontrar el modelo con mejor desemepeño.Los modelos se evaluaron teniendo en cuenta las metricas relevantes como las curvas ROC, sus matrices de confusion y curvas de aprendizaje, comparando cual de los dos modelos que se entrenaron fue el mejor.

# Contenidos del respositorio
1. epidata.csv: Archivo con los datos brutos (Sin procesar)
2. exploracion.ipynb: Archivo donde se fabrican las graficas y datos para entender al dataset
3. preprocesado.ipynb: Archivo donde se procesaron los datos de cara al entrenamiento
4. modelo1.ipynb: Archivo de entranmiento de un RandomForest Classifier
5. modelo2.ipynb: Archivo de entrenamiento de un LogisticRegression
6. comparacion.ipynb: Archivo donde se compara el comportamiento de los dos modelos.
7. informe.pdf: Archivo con el informe donde se sintetiza todo el proceso realizado y los resultados obtenidos.
8. anexos.zip: Archivo que contiene una carpeta de anexos que es necesaria para la ejecucion del archivo de comparacion **Extraer antes de ejecutar**
9. resultados_modelos.json: Archivo de tipo json para guardar algunas metricas importantes de los modelos **Es necesario para el archivo de comparacion**
