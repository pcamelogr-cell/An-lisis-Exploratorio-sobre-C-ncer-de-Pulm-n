# Analisis Exploratorio sobre Cancer de Pulmon

Este proyecto forma parte del curso Programación II, grupo G-VI. En este proyecto analizaremos 800.000 historias reales de personas diagnosticadas con cáncer de pulmón, con el objetivo de comprender patrones de supervivencia y los factores que influyen en la mortalidad. Utilizaremos herramientas de estadística descriptiva, manejo de datos y visualización para realizar un análisis completo de esta enfermedad que afecta a millones de familias en todo el mundo.

Trabajaremos con Python (Pandas) y emplearemos GitHub para la colaboración entre los integrantes del proyecto.

Al analizar estos datos, estamos aportando a la comprensión de una de las enfermedades más mortales en la historia de la humanidad.

## Integrantes
- Paula Camelo - Lider de Proyecto
- Isabella Calderón Pensamiento
- Laura Valentina Franco Guarumo
- Harold Andres Burgos Muñoz


## Estructura del Dataset
Este dataset fue sacado de kaggle, para claridad de alguna duda que surja con respecto a su procedencia , adjunto el link del dataset.
https://www.kaggle.com/datasets/amankumar094/lung-cancer-dataset

El conjunto de datos utilizado contiene 800.000 registros y 20 columnas, que incluyen información demográfica, clínica y de antecedentes médicos de pacientes diagnosticados con cáncer de pulmón. El dataset cuenta con: Variables categóricas: género, país, etapa del cáncer, historial familiar, tipo de tratamiento.

Variables numéricas continuas: edad, pack_years.

Variables numéricas discretas: presencia o ausencia de enfermedades.

Fechas importantes: fecha de diagnóstico y fecha de fin del tratamiento.


## Diccionario del Dataset

- **Variables Numéricas:**  
  - **id:** Identificador único del paciente.  
  - **age:** Edad del paciente.  
  - **pack_years:** Años-fumador acumulados.

- **Variables Categóricas:**  
  - **gender:** Género del paciente.  
  - **country:** País de origen del paciente.  
  - **cancer_stage (ordinal):** Etapa del cáncer (I, II, III, IV).  
  - **family_history (binaria):** Antecedentes familiares de cáncer (Sí/No).  
  - **smoking_history:** Historial de tabaquismo.  
  - **treatment_type:** Tipo principal de tratamiento recibido.

- **Variables Binarias:**  
  - **copd:** Presencia de enfermedad pulmonar obstructiva crónica.  
  - **pneumonia:** Antecedentes de neumonía.  
  - **diabetes:** Diagnóstico de diabetes.  
  - **heart_disease:** Presencia de enfermedad cardíaca.  
  - **stroke:** Antecedente de accidente cerebrovascular.  
  - **liver_disease:** Enfermedad hepática.  
  - **kidney_disease:** Enfermedad renal.  
  - **other_cancer:** Presencia de otros cánceres previos.  
  - **survived:** Estado final del paciente (1 = sobrevivió, 0 = falleció).

- **Variables Tipo Fecha:**  
  - **diagnosis_date:** Fecha del diagnóstico de cáncer de pulmón.  
  - **end_treatment_date:** Fecha de finalización del tratamiento.

  
  

## Conclusiones

- En este conjunto de datos, la Cirugía ofrece las mejores probabilidades de supervivencia al paciente, cuenta con un porcentaje (22,15%) de supervivencia, mientras que la Quimioterapia ofrece los peoress resultados con una tasa de muertes del (78.13%), aunque la diferencia entre unos metodos y los otros no es mucha, cuando hablamos de vidas humanas son porcentajes valiosos asi que resaltamos la importancia de aplicar enfoques que incluyan el procedimiento quirúrgico.

- En este conjunto de datos, la Cirugía ofrece las mejores probabilidades de supervivencia al paciente, cuenta con un porcentaje (22,15%) de supervivencia, mientras que la Quimioterapia ofrece los peoress resultados con una tasa de muertes del (78.13%), aunque la diferencia entre unos metodos y los otros no es mucha, cuando hablamos de vidas humanas son porcentajes valiosos asi que resaltamos la importancia de aplicar enfoques que incluyan el procedimiento quirúrgico.

- Una observación importante es que aunque los adultos mayores nunca hayan fumado, su edad los hace mas propensos al desarrollo de cáncer de pulmón. Esto puede deberse a que, con el paso de los años pueden adquirir diversas enfermedades, lo cual debilita sus cuerpos o el estilo de vida que llevaron en su juventud, es decir sean ex fumadores o no , los adultos mayores son mucho mas propensos a desarrollar cancer de pulmon que un joven adicto al cigarrillo, por lo que la edad se vuelve un factor importante en el desarrollo y la  vulnerabilidad de esta enfermedad.

- Determinamos que los pacientes de mayor riesgo son, en su mayoría, personas mayores de 70 años, con dos o más enfermedades adicionales y con un cáncer en etapa IV. También vimos algunos casos de pacientes jóvenes (menores de 40) que ya presentaban cáncer avanzado, así como pacientes con antecedentes familiares y hábitos como fumar indican que tanto la genética como el estilo de vida influyen de manera importante en la supervivencia.

- La base de datos muestra que la supervivencia es extremadamente baja y está determinada principalmente por la etapa del cáncer al ser detectado. Los tratamientos con cirugía muestran mejores resultados porque se aplican en fases tempranas. Se identifican dos grupos críticos: jóvenes con cáncer avanzado y pacientes con una combinación de historial familiar y tabaquismo, lo que muestra la urgencia de mejorar la detección temprana. La clave para que haya una menor taza de mortalidad es diagnosticar a tiempo y manejar las condiciones de alto riesgo del paciente, como la edad y las comorbilidades.

