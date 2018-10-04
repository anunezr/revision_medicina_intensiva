# revision_medicina_intensiva
Dataframe y scripts de ejemplo para el capitulo de Revision de Medicina Intensiva

Vamos a utilizar una base de datos de pacientes de UCI para intentar conseguir un modelo predictivo lo más preciso posible.
Tenemos que tener en cuenta que se trata de conseguir un modelo de clasificación con dos posibles resultados (vivo o exitus), y que la incidencia de ambos resultados está muy disbalanceada en la base de datos de ejemplo (la mortalidad en esta cohorte de pacientes es del 6.7%), por lo que si predecimos que todos los pacientes van a sobrevivir obtendremos una tasa de aciertos del 93.3%.

Vamos a utilizar este ejemplo para practicar una serie de modelos predictivos con python y la biblioteca scikit-learn, a la vez que avanzamos paulatinamente en la mejora de los algoritmos predictivos hasta llegar al que consideremos óptimo.

Nuestro objetivo es conseguir el modelo con la mejor AUROC.

Los modelos que utilizaremos son:

Perceptron

Linear regression

SVM

Decision trees

Ensemble models

Deep learning

Cuadernos:

1) Estadistica básica: realizamos un análisis preliminar de los datos usando las bibliotecas de Python para ello. Esto puede hacerse también en R.

2) Perceptron: utilizamos un perceptron como modelo predictivo



