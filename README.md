Machine Learning - Predicción de Supervivencia en el Titanic
Este repositorio contiene un script simple para predecir la supervivencia de un pasajero en el Titanic utilizando
un modelo de machine learning previamente entrenado. El modelo ha sido entrenado con un conjunto de datos que incluye información sobre pasajeros del Titanic.

Parámetros de Entrada
El script utiliza varios parámetros para hacer la predicción:

Uso del Notebook
- Asegúrate de tener Jupyter Notebook instalado.
- Abre el notebook prediccion_supervivencia.ipynb.
- Ejecuta las celdas del notebook.

En el notebook, se cargarán automáticamente los datos desde el archivo CSV "train" y se realizará la predicción utilizando el vector nueva_persona.

Clase del Boleto (Pclass): Indica la clase en la que viajaba el pasajero (primer parámetro).
Edad (Age): Edad de la persona (segundo parámetro).
Número de Hermanos/Cónyuge a bordo (SibSp): Indica si la persona tiene hermanos o cónyuge a bordo (tercer parámetro).
Número de Padres/Hijos a bordo (Parch): Indica si la persona tiene padres o hijos a bordo (cuarto parámetro).
Valor del Ticket (Fare): Valor del ticket pagado por el pasajero (quinto parámetro).
Parametros restantes rellenar en base a x ( X.head() )

Notas Adicionales
Asegúrate de ajustar los valores de nueva_persona según sea necesario antes de ejecutar las celdas del notebook.
