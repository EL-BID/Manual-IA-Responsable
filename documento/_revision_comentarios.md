############# 02-07-2020 #############
Estoy de acuerdo de que el criterio de evaluación sea el análisis de costo beneficio
pero sí creo que debemos de mencionar las métricas y las razones de por qué no son
suficientes (accuracy, precision, etc) porque si no se ve como omisión, además de que
se mencionan en equidad diferencial en donde se tiene que evaluar en función de alguna de ellas. 

El ejemplo de (sesgo en procesamiento de caras)**: - No me parece un caso claro de sobre y sub ajuste, quizá es más un desbalance de clase. 
Entiendo que la idea es que durante el entrenamiento se puede buscar ajustar menos para intentar que el modelo solo aprenda patrones de la cara 
sin aprender atributos como color. Pero es complicado eso por el tipo de ejemplo.

Manejamos de forma confusa la equidad del outcome vs la equidad del error. Creo que nos podemos quedar solo en equidad de error, 
entonces mis comentarios de cuotas quizá no van.

En el word les ponía si podemos agregar “Equal Accuracy”: “Group Thresholds” y Justicia contrafactual que son los que se usan en facets. Me 
lo quedo pendiente y lo agrego más tarde. 

#####################################
