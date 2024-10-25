# Predicción de Satisfacción con la Carrera

## Descripción del Proyecto
Este proyecto explora un conjunto de datos recopilados de estudiantes universitarios para predecir su satisfacción con su carrera, basándose en diversos factores demográficos y académicos.

## Resumen del Conjunto de Datos
El conjunto de datos incluye detalles de estudiantes universitarios obtenidos a través de un formulario de Google. Contiene atributos como:
- Cursos de certificación completados
- Género
- Departamento
- Rendimiento académico
- Pasatiempos
- Hábitos de estudio
- Expectativas salariales

Nuestra variable objetivo es **"Do you like your degree?"**, que indica si a los estudiantes les gusta su carrera o no.

## Tipo de Problema
Este es un **problema de clasificación binaria**, ya que nuestro objetivo es predecir si a un estudiante le gusta su carrera (clase positiva) o no (clase negativa). Entrenaremos modelos de aprendizaje automático utilizando los datos proporcionados para predecir la probabilidad de satisfacción con la carrera de un estudiante.

## Resumen del Análisis
1. Carga de librerías necesarias y datos
2. Análisis preliminar de los datos y preparación de los mismos
3. Elección de la métrica
4. Ajuste y selección de algoritmos y sus parámetros
5. Evaluación de algoritmos
6. Conclusiones

## Solución
La solución se encuentra en el archivo `notebooks/Degree_Satisfaction_Prediction.ipynb`.

## Conclusiones
Basándonos en los resultados de precisión (accuracy) obtenidos, el modelo Random Forest sobresale con la precisión más alta de 0.987. Esto indica que Random Forest tiene el mejor desempeño en términos de precisión de predicción en comparación con los otros modelos evaluados en este estudio. Sin embargo, es esencial tener en cuenta que estos resultados se basan en la validación cruzada y no garantizan necesariamente un rendimiento óptimo en datos no vistos. 

## Requisitos

Este proyecto requiere las siguientes librerías de Python:

- **pandas**: Manejo y análisis de datos
- **numpy**: Operaciones y funciones matemáticas
- **missingno**: Visualización de valores faltantes en el conjunto de datos
- **sklearn**: Modelos y herramientas para el aprendizaje automático
- **xgboost**: Implementación del algoritmo de Gradient Boosting
- **ydata_profiling**: Generación de reportes de análisis exploratorio de datos
- **matplotlib**: Generación de gráficos y visualizaciones

Puedes instalar las librerías necesarias usando el siguiente comando:

```bash
pip install pandas numpy missingno scikit-learn xgboost ydata-profiling matplotlib

