# Analisis Exploratorio sobre Cancer de Pulmon

Este proyecto forma parte del curso Programación II, grupo G-VI. En este proyecto analizaremos 800.000 historias reales de personas diagnosticadas con cáncer de pulmón, con el objetivo de comprender patrones de supervivencia y los factores que influyen en la mortalidad. Utilizaremos herramientas de estadística descriptiva, manejo de datos y visualización para realizar un análisis completo de esta enfermedad que afecta a millones de familias en todo el mundo.

Trabajaremos con Python (Pandas) y emplearemos GitHub para la colaboración entre los integrantes del proyecto.

Al analizar estos datos, estamos aportando a la comprensión de una de las enfermedades más mortales en la historia de la humanidad.

## Integrantes
- Paula Camelo - Lider de Proyecto
- Isabella Calderón Pensamiento
- Laura Valentina Franco Guarumo



## Estructura del Dataset

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

  
  



## Intruciones de cómo ejecutar

1. Activar entorno virtual: `source .venv/Scripts/activate`
2. Instalar dependencias: `pip install -r requirements.txt`


## Conclusiones

