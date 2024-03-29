# Bienvenido al Proyecto de Análisis de Datos de Diabetes

## Acerca del Dataset

La diabetes es una de las enfermedades crónicas más prevalentes en el mundo,, afectando a millones de personas cada año y ejerciendo una carga financiera significativa en la economía. La diabetes es una enfermedad crónica grave en la que los individuos pierden la capacidad de regular eficazmente los niveles de glucosa en la sangre, lo que puede llevar a una disminución de la calidad de vida y la esperanza de vida. Las complicaciones asociadas con niveles crónicamente altos de azúcar en la sangre incluyen enfermedades cardíacas, pérdida de visión, amputación de miembros inferiores y enfermedad renal.

El Behavioral Risk Factor Surveillance System (BRFSS) es una encuesta telefónica relacionada con la salud que se recopila anualmente por los CDC. Cada año, la encuesta recopila respuestas de más de 400,000 estadounidenses sobre comportamientos relacionados con la salud, enfermedades crónicas y el uso de servicios preventivos. Para este proyecto, se utilizó un archivo csv del conjunto de datos disponible en Kaggle para el año 2015. Este conjunto de datos original contiene respuestas de 441,455 individuos y tiene 330 características. Estas características son preguntas directamente formuladas a los participantes o variables calculadas basadas en las respuestas individuales de los participantes.

Este proyecto utiliza tres archivos de datos:

- **diabetes_012_health_indicators_BRFSS2015.csv:** Un conjunto de datos limpio de 253,680 respuestas a la encuesta BRFSS2015. La variable objetivo Diabetes_012 tiene 3 clases: 0 para no diabetes o solo durante el embarazo, 1 para prediabetes y 2 para diabetes. Este conjunto de datos tiene 21 variables de características.

- **diabetes_binary_5050split_health_indicators_BRFSS2015.csv:** Un conjunto de datos limpio de 70,692 respuestas a la encuesta BRFSS2015. Tiene una división equitativa del 50-50 de encuestados sin diabetes y con prediabetes o diabetes. La variable objetivo Diabetes_binary tiene 2 clases: 0 para no diabetes y 1 para prediabetes o diabetes. Este conjunto de datos tiene 21 variables de características y está balanceado.

- **diabetes_binary_health_indicators_BRFSS2015.csv:** Un conjunto de datos limpio de 253,680 respuestas a la encuesta BRFSS2015. La variable objetivo Diabetes_binary tiene 2 clases: 0 para no diabetes y 1 para prediabetes o diabetes. Este conjunto de datos tiene 21 variables de características y no está balanceado.

## Preguntas de Investigación

Algunas de las preguntas de investigación exploradas en este proyecto son:

1. ¿Pueden las preguntas de la encuesta BRFSS proporcionar predicciones precisas sobre si un individuo tiene diabetes?

2. ¿Qué factores de riesgo son más predictivos del riesgo de diabetes?

3. ¿Podemos utilizar un subconjunto de los factores de riesgo para predecir con precisión si alguien tiene diabetes?

4. ¿Podemos crear un formulario corto de preguntas de la BRFSS utilizando selección de características para predecir con precisión si alguien podría tener diabetes o está en alto riesgo de diabetes?

## Inspiración

Este proyecto se inspira en el trabajo de Zidian Xie et al. sobre la creación de modelos de predicción de riesgos para la diabetes tipo 2 utilizando técnicas de aprendizaje automático con la BRFSS de 2014.

¡Gracias por explorar este proyecto!

