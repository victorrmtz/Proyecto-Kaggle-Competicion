# Kaggle-Competicion

## 🎯 OBJETIVOS

- Preparar los datos para los diversos modelos (proceso empírico) 
- Entrenar y Testear modelos de Machine Learning
- Subir los resultados con el mejor modelo entrenado de Machine Learning
- Presentación en la carpeta de 'PPTS'

## 🚶 PASOS DE LA PREDICCIÓN

1. Borrar columna de salary en el DataFrame del Testeo
2. Limpieza del DataFrame
- Creación de diccionarios para cambiar valores.
- Concatenar DataFrames(Testeo y Salario)
- Cambio de String a Int.
3. Inicializar, entrenar los modelos de Machine Learning.
4. Predición sobre el mismo Dataframe.
5. Cogemos el mejor modelo y lo entrenamos
6. Exportar predicciones finales.

## 📚RECURSOS

- data (Carpeta con los Datos y las predicciones finales)
- Salaries_data.csv (Datos para trabajar)
- Testeo.csv (Datos para predecir)
- Muestra.csv (Ejemplo de resultados que deben subir a Kaggle)
- src (Carpeta con todos los modelos de Machine Learning)
- resultado_gbr_contodo_curren.csv (Mejores Predicciones)

## 🔍INFO DE COLUMNAS 
- *work_year:* The year the salary was paid.
- *experience_level:* The experience level in the job during the year
- *employment_type:* The type of employment for the role
- *job_title:* The role worked in during the year.
- *salary:* The total gross salary amount paid.
- *salary_currency:* The currency of the salary paid as an ISO 4217 currency code.
- *salaryinusd:* The salary in USD
- *employee_residence:* Employee's primary country of residence in during the work year as an ISO 3166 country code.
- *remote_ratio:* The overall amount of work done remotely
- *company_location:* The country of the employer's main office or contracting branch
- *company_size:* The median number of people that worked for the company during the year