
Contexto

La diabetes es una de las enfermedades crónicas más prevalentes en el mundo, afectando a millones de personas cada año y ejerciendo una carga financiera significativa en la economía. La diabetes es una enfermedad crónica grave en la que los individuos pierden la capacidad de regular efectivamente los niveles de
glucosa en la sangre, lo que puede llevar a una reducción de la calidad de vida y de la esperanza de vida. Después de que diferentes alimentos se descomponen en azúcares durante la digestión, los azúcares se liberan en el torrente sanguíneo. Esto señala al páncreas para que libere insulina. 
La insulina ayuda a que las células dentro del cuerpo utilicen esos azúcares en el torrente sanguíneo como energía. La diabetes se caracteriza generalmente por el cuerpo que no produce suficiente insulina o que no puede usar la insulina que se produce tan efectivamente como se necesita.

Complicaciones como enfermedades cardíacas, pérdida de visión, amputación de miembros inferiores y enfermedad renal están asociadas con niveles crónicamente altos de azúcar en la sangre en aquellos con diabetes. Si bien no hay cura para la diabetes, estrategias como perder peso, comer saludablemente, ser activo y recibir tratamientos médicos pueden mitigar los daños de esta enfermedad en muchos pacientes. El diagnóstico temprano puede conducir a cambios en el estilo de vida y un tratamiento más efectivo, lo que hace que los modelos predictivos de riesgo de diabetes sean herramientas importantes para los funcionarios de salud pública.

La escala de este problema también es importante de reconocer. Los Centros para el Control y la Prevención de Enfermedades han indicado que, hasta 2018, 34.2 millones de estadounidenses tienen diabetes y 88 millones tienen prediabetes. Además, los CDC estiman que 1 de cada 5 diabéticos y aproximadamente 8 de cada 10 prediabéticos desconocen su riesgo. Si bien existen diferentes tipos de diabetes,
la diabetes tipo II es la forma más común y su prevalencia varía según la edad, la educación, los ingresos, la ubicación, la raza y otros determinantes sociales de la salud. Gran parte de la carga de la enfermedad recae también en aquellos de menor estatus socioeconómico. La diabetes también representa una gran carga para la economía, 
con costos de diabetes diagnosticada de aproximadamente $327 mil millones de dólares y costos totales con diabetes no diagnosticada y prediabetes que se aproximan a los $400 mil millones de dólares anualmente.

Contenido

El Sistema de Vigilancia de Factores de Riesgo Conductuales (BRFSS) es una encuesta telefónica relacionada con la salud que se recopila anualmente por los CDC. Cada año, la encuesta recopila respuestas de más de 400,000 estadounidenses sobre comportamientos relacionados con la salud, condiciones de salud crónicas y el uso de servicios preventivos. Se ha realizado cada año desde 1984. Para este proyecto, se utilizó un archivo csv del conjunto de datos disponible en Kaggle para el año 2015. Este conjunto de datos original contiene respuestas de 441,455 individuos y tiene 330 características. Estas características son preguntas directamente hechas a los participantes o variables calculadas basadas en las respuestas individuales de los participantes.

Este conjunto de datos contiene 3 archivos:

diabetes_012_health_indicators_BRFSS2015.csv es un conjunto de datos limpio de 253,680 respuestas a la encuesta BRFSS2015 de los CDC. La variable objetivo Diabetes_012 tiene 3 clases. 0 es para no diabetes o solo durante el embarazo, 1 es para prediabetes y 2 es para diabetes. Hay desequilibrio de clases en este conjunto de datos. Este conjunto de datos tiene 21 variables de características.
diabetes_binary_5050split_health_indicators_BRFSS2015.csv es un conjunto de datos limpio de 70,692 respuestas a la encuesta BRFSS2015 de los CDC. Tiene una división equitativa del 50-50 de encuestados sin diabetes y con prediabetes o diabetes. La variable objetivo Diabetes_binary tiene 2 clases. 0 es para no diabetes y 1 es para prediabetes o diabetes. Este conjunto de datos tiene 21 variables de características y está equilibrado.
diabetes_binary_health_indicators_BRFSS2015.csv es un conjunto de datos limpio de 253,680 respuestas a la encuesta BRFSS2015 de los CDC. La variable objetivo Diabetes_binary tiene 2 clases. 0 es para no diabetes y 1 es para prediabetes o diabetes. Este conjunto de datos tiene 21 variables de características y no está balanceado.
Exploración

Algunas de las siguientes preguntas de investigación podrían ser exploradas utilizando este conjunto de datos:

¿Pueden las preguntas de la encuesta del BRFSS proporcionar predicciones precisas sobre si un individuo tiene diabetes?
¿Qué factores de riesgo son más predictivos del riesgo de diabetes?
¿Podemos utilizar un subconjunto de los factores de riesgo para predecir con precisión si un individuo tiene diabetes?
¿Podemos crear un formulario corto de preguntas del BRFSS utilizando selección de características para predecir con precisión si alguien podría tener diabetes o está en alto riesgo de diabetes?
Reconocimientos

Es importante reiterar que no creé este conjunto de datos, es solo un conjunto de datos limpio y consolidado creado a partir del conjunto de datos BRFSS 2015 ya disponible en Kaggle. Ese conjunto de datos se puede encontrar aquí y el cuaderno que utilicé para la limpieza de datos se puede encontrar aquí.

Inspiración

Zidian Xie et al para la construcción de modelos de predicción de riesgos para la diabetes tipo 2 utilizando técnicas de aprendizaje automático utilizando el BRFSS 2014 fue la inspiración para crear este conjunto de datos y explorar el BRFSS en general. Enlace

Por favor, asegúrate de dar crédito adecuado a los creadores originales del conjunto de datos y a cualquier otra persona o fuente mencionada en tu trabajo.
