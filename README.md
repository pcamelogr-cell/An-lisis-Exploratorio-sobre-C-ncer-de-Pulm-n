# Analisis Exploratorio sobre Cancer de Pulmon

Este proyecto forma parte del curso Programación II, grupo G-IV. En este proyecto analizaremos 800.000 historias reales de personas diagnosticadas con cáncer de pulmón, con el objetivo de comprender patrones de supervivencia y los factores que influyen en la mortalidad. Utilizaremos herramientas de estadística descriptiva, manejo de datos y visualización para realizar un análisis completo de esta enfermedad que afecta a millones de familias en todo el mundo.

Trabajaremos con Python (Pandas) y emplearemos GitHub para la colaboración entre los integrantes del proyecto.

Al analizar estos datos, estamos aportando a la comprensión de una de las enfermedades más mortales en la historia de la humanidad.

## Integrantes
- Paula Camelo - Lider de Proyecto


## Estructura del Dataset

El conjunto de datos utilizado contiene 800.000 registros y 20 columnas, que incluyen información demográfica, clínica y de antecedentes médicos de pacientes diagnosticados con cáncer de pulmón. El dataset cuenta con: Variables categóricas: género, país, etapa del cáncer, historial familiar, tipo de tratamiento.

Variables numéricas continuas: edad, pack_years.

Variables numéricas discretas: presencia o ausencia de enfermedades.

Fechas importantes: fecha de diagnóstico y fecha de fin del tratamiento.


## Diccionario del Dataset

- Variables Numéricas:
  ID, Age, Pack_Years.
  
- Variables Categóricas:
  Gender, Country, Cancer_Stage (ordinal), Family_History (Binaria), Smoking_Story, Treatment_type.
  
- Variables Binarias:
  Copd, Pneumonia, Diabetes, Heart_Disease, Stroke, Liver_Disease, Kidney_Disease, Other_Cancer, Survived.
  
- Variables Tipo Fecha:
  Diagnosis_Date, End_Treatment_Date. 
  
  





## Cómo ejecutar
1. Activar entorno virtual: `source .venv/Scripts/activate`
2. Instalar dependencias: `pip install -r requirements.txt`


## Conclusiones

