# Bienvenido al Proyecto de Análisis de Datos de Diabetes

## Acerca del Dataset

La diabetes es una de las enfermedades crónicas más prevalentes en el mundo,, afectando a millones de personas cada año y ejerciendo una carga financiera significativa en la economía. La diabetes es una enfermedad crónica grave en la que los individuos pierden la capacidad de regular eficazmente los niveles de glucosa en la sangre, lo que puede llevar a una disminución de la calidad de vida y la esperanza de vida. Las complicaciones asociadas con niveles crónicamente altos de azúcar en la sangre incluyen enfermedades cardíacas, pérdida de visión, amputación de miembros inferiores y enfermedad renal.

El Behavioral Risk Factor Surveillance System (BRFSS) es una encuesta telefónica relacionada con la salud que se recopila anualmente por los CDC. Cada año, la encuesta recopila respuestas de más de 400,000 estadounidenses sobre comportamientos relacionados con la salud, enfermedades crónicas y el uso de servicios preventivos. Para este proyecto, se utilizó un archivo csv del conjunto de datos disponible en Kaggle para el año 2015. Este conjunto de datos original contiene respuestas de 441,455 individuos y tiene 330 características. Estas características son preguntas directamente formuladas a los participantes o variables calculadas basadas en las respuestas individuales de los participantes.

Este proyecto utiliza tres archivos de datos:

- **diabetes_012_health_indicators_BRFSS2015.csv:** Un conjunto de datos limpio de 253,680 respuestas a la encuesta BRFSS2015. La variable objetivo Diabetes_012 tiene 3 clases: 0 para no diabetes o solo durante el embarazo, 1 para prediabetes y 2 para diabetes. Este conjunto de datos tiene 21 variables de características.

- **diabetes_binary_5050split_health_indicators_BRFSS2015.csv:** Un conjunto de datos limpio de 70,692 respuestas a la encuesta BRFSS2015. Tiene una división equitativa del 50-50 de encuestados sin diabetes y con prediabetes o diabetes. La variable objetivo Diabetes_binary tiene 2 clases: 0 para no diabetes y 1 para prediabetes o diabetes. Este conjunto de datos tiene 21 variables de características y está balanceado.

- **diabetes_binary_health_indicators_BRFSS2015.csv:** Un conjunto de datos limpio de 253,680 respuestas a la encuesta BRFSS2015. La variable objetivo Diabetes_binary tiene 2 clases: 0 para no diabetes y 1 para prediabetes o diabetes. Este conjunto de datos tiene 21 variables de características y no está balanceado.



# Welcome to the Diabetes Data Analysis Project

## About the Dataset

Diabetes is among the most prevalent chronic diseases in the world, impacting millions of peaple each year and exerting a significant financial burden on the economy. Diabetes is a serious chronic disease in which individuals lose the ability to effectively regulate levels of glucose in the blood, leading to reduced quality of life and life expectancy. Complications associated with chronically high levels of sugar remaining in the bloodstream for those with diabetes include heart disease, vision loss, lower-limb amputation, and kidney disease.

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants or calculated variables based on individual participant responses.

This project utilizes three data files:

- **diabetes_012_health_indicators_BRFSS2015.csv:** A clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes: 0 for no diabetes or only during pregnancy, 1 for prediabetes, and 2 for diabetes. This dataset has 21 feature variables.

- **diabetes_binary_5050split_health_indicators_BRFSS2015.csv:** A clean dataset of 70,692 survey responses to the CDC's BRFSS2015. It has an equal 50-50 split of respondents with no diabetes and with either prediabetes or diabetes. The target variable Diabetes_binary has 2 classes: 0 for no diabetes, and 1 for prediabetes or diabetes. This dataset has 21 feature variables and is balanced.

- **diabetes_binary_health_indicators_BRFSS2015.csv:** A clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_binary has 2 classes: 0 for no diabetes, and 1 for prediabetes or diabetes. This dataset has 21 feature variables and is not balanced.


