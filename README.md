# pima
Análisis y modelo predictivo del dataset Pima Indians Diabetes Database de Kaggle.

Este notebook utiliza el dataset que se puede encontrar en la siguiente URL: https://www.kaggle.com/uciml/pima-indians-diabetes-database

Primero se hace un interesante EDA del dataset, enocntrándonos valores erróneos que hay que corregir. También nos encontramos con que el dataset está desequilibrado, dado que hay 2/3 de las observaciones de pacientes sin diabetes y solo 1/3 con la enfermedad, aspecto que también hay que tratar.

Después se hace una validación cruzada para ir descartando modelos y quedarnos solo con tres (RandomForest, ADABoost y Regresión Logística). Entrenamos con los tres (después de dividir el modelo en set de entrenamiento y de test) y después aplicamos el modelo a todo el dataset.

Este es un ejemplo de dataset donde no debería emprearse una red neuronal, ya que el número de observaciones es muy bajo (<1000).
