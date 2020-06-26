
#############

- This question appears awkward. Is the right context this - "This manual is intended to help navigate when ML may be used in decision-making, where the decision may have significant impact or risk, or where there is the potential for discriminatory or unfair outcomes."

Los métodos de ML siempre se usan para tomar decisiones (en otro caso es irrelevante). El manual es más general, pues
si se hace el proceso, puede haber impactos y riesgos importantes en general, y en particular en resultados discriminatorios.

##########

- A note: where there is a consequential decision that a human should make the ultimate decision and the role of AI is to augment or assist in that decisionmaking.

Agregamos comentario de que en situaciones de costo/beneficio alto, debe usarse el modelo de decisión asistido.

##############

- This section raises the question about whether AI is fit for a particular purpose if used to make a prediction. There may be some predictive use cases where it is not appropriate to use the technology - so the threshold questions are 1. Should AI be used; and 2. Is the technology fit for the purpose.

Si, la validación en el contexto del problema puede llevar a decidir que 1 es cierto y/o 2 es cierto. Creemos que esto es un
supuesto. 

###########

- Recibí comentarios que “metrica” no es fácil de comprender y la usamos indistintamente para variable objetivo, métricas calculadas de equidad algorítmica. Qué pones? La otra es explicar arriba de alguna forma.

usaremos "Métrica objetivo" cuando nos referimos a la variable a predecir, y "métrica de evaluación" en el otro caso.

###########

- t is important that the purposes or policies are also not biased. A suggestion is that this section include ", and the potential bias of data used is considered."

La creación de políticas mal pensadas o maliciosas está fuera del scope del documento.

#########

. En términos generales, la fuente de incertidum- bre deriva de tres áreas: 
1 las deficiencias de la información (incompleta, errónea, imprecisa), 
2 las características propias del mundo real (no determinista: mismas causas producen efectos diferentes en distintas personas) y 
3  las deficiencias de los modelos que intentan explicarlo (incompleto, inexacto)

Aquí no hablamos de fuente de incertidumbre (por ejemplo, el no determinismo del proceso real), ni de métodos deficientes
para modelar fenómenos. Hablamos en general de ausencia de información importante que sea requisito para acercarse
apropiadamente al problema.

##########
El físico de la universidad de Cataluña pidió busquemos una forma de que un público que no sepa estadística entiend

Agregamos ejemplos. Pero si no saben estadística a este nivel, es un warning sign impórtante.

##############
quizá convenga como bullet adicional, tocar el reto de la sobrerepresentación de algun grupo como algo que mitigar tmb

Agregamos lo de sobrerrepresentación de grupos mayoritarios.

##############
Este iría acá o en errores de validación?

Creemos que aquí, porque puede ser que los datos de entrenamiento sean muy deficientes de multiples maneras.
Sin embargo, si tenemos un conjunto de validación bien construido, es posible detectar fallas y problemas y desempeño
malo general o en subgrupos.

################
Comparación causal y decir que muchas veces los datos con los que se entrenan los modelos no son iguales a los que se encuentra ya en producción. Si es esto último, quizá se debería de tratar en evaluación?

El problema no es que los datos de producción no sean los de entrenamiento. El problema es sobreinterpretación o extrapolación
en cualquier conjunto de datos: entrenamiento, validación o producción.


##############3
Hay alguna bibliografía que recomienden para otros casos. Ejemplo construcción de validación para series de tiempo

Agrtegamos referencia para serires de tiempo

############3
quizá vale en algún lado indicar que se deberá de establecer por expertos en la materia y contexto cuál es el rango de error aceptable y la transparencia en informar porqué el rengo

Agregamos explicación de esto.












##############
No se entiende mucho este punto. 
Esto cubre obligación legal? Por ejemplo, en algunos tipos de créditos si rechazas a alguien estás obligado a decirle por qué. 
En programas sociales para cuenta pública por ley tienes que justificar a tu población beneficiaria

Agregamos aspectos legales y sociales (tomadores de decisiones y afectados)


#####
y de ahí hilarlo con el tema de trazabilidad, auditabilidad?

Esta parte realmente es una sección separada que agregamos.**


#####
¿valdría la pena incluir temas como incluir en el diseño y ejecución mecanismos para human review de la decisión o resultado? si bien esto cae fuera de lo "técnico" creo que ale la pena hacer la mención ya que para hacerlo real, tiene que tener el modelo un sistema de transparencia (porqué se tomaron decisiones, datos, etc,) trazabilidad, etc. que sí cae dentro de lo técnico . #fuelforthought

Si, podemos poner algo de que debe existir también revisión humana de los resultados de manera periódica, pues
existen problemas que a veces no se miden. Agregamos esto en retos de modelación (errores no medidos y evaluación humana)

