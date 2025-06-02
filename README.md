# Descripcion del proyecto
En este repositorio se encuentra la entrega del proyecto final del curso de programación.

Fue desarrollado por Samuel Mercado y Martin Perez.

El proyecto consistió en el entrenamiento de dos modelos de aprendizaje automático para clasificar un conjunto de personas en pacientes sanos (sin epilepsia) y enfermos (con epilepsia) de acuerdo con una señal de electroencefalograma de cada uno de ellos. Para ello se creó un flujo de trabajo que inició con la exploración de los datos para analizar su estructura y las posibles complicaciones que podrían surgir de la naturaleza de estos.

Luego se procedió con el procesado de estos para que fueran útiles para entrenar los modelos.

Y por último el entrenamiento de los modelos, haciendo uso de algoritmos para ajustar los hiperparámetros y poder encontrar el modelo con mejor desempeño. Los modelos se evaluaron teniendo en cuenta las métricas relevantes como las curvas ROC, sus matrices de confusión y curvas de aprendizaje, comparando cuál de los dos modelos que se entrenaron fue el mejor.

# Contenidos del repositorio

1. epidata.csv: Archivo con los datos brutos (Sin procesar)
2. exploracion.ipynb: Archivo donde se fabrican las gráficas y datos para entender el dataset
3. preprocesado.ipynb: Archivo donde se procesaron los datos de cara al entrenamiento
4. modelo1.ipynb: Archivo de entrenamiento de un RandomForest Classifier
5. modelo2.ipynb: Archivo de entrenamiento de un LogisticRegression
6. comparacion.ipynb: Archivo donde se compara el comportamiento de los dos modelos
7. informe.pdf: Archivo con el informe donde se sintetiza todo el proceso realizado y los resultados obtenidos
8. anexos.zip: Archivo que contiene una carpeta de anexos que es necesaria para la ejecución del archivo de comparación. **Extraer antes de ejecutar**
9. resultados_modelos.json: Archivo de tipo JSON para guardar algunas métricas importantes de los modelos. **Es necesario para el archivo de comparación**
