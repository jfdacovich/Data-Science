### 01 - Prueba técnica Python Data Analyst



Descripción La prueba tiene como objetivo desarrollar una analítica sobre un dataset volcado en una base de datos relacional e implementar un pipeline de ETL que realice cierto procesado y agregación. En la base de datos te encontrarás dos tablas, **orders**, con información a nivel de transacción, y **merchants**, con información a nivel de comercio.

Los datos de acceso a la base de datos son los siguientes (puedes explorar este mismo
repositorio en otra herramienta como DBeaver)

Facilitamos acceso de solo lectura a la base de datos:

- Usuario: postgres

- Contraseña: password

- DB name: dbneoland

- URI completa: postgresql://postgres:password@datachallenge.
  co4whz3w2rtn.us-east-1.rds.amazonaws.com:5432/dbneoland

  

  La prueba debe desarrollarse con Python 3. Puedes utilizar todas las librerías que te resulte necesario, por ejemplo pandas, plotly/bokeh o SQLAlchemy.

  

  ### Tarea 1: Análisis del dataset

  Apoyándote en uno o varios Jupyter Notebooks, realiza un análisis sobre los datos de la
  tabla orders contemplando los siguientes puntos:

  1. Análisis sencillo del dataset proporcionado variable a variable, obteniendo
  métricas resumen o representaciones gráficas de cada una de ellas. ¿En base a este análisis, crees que alguna variable debería ser descartada?
  2. Realiza un scatter plot en el que se compare el volumen financiado en un créditocon el número de cuotas elegido (numbre_instalments). ¿Que se observa?
  3. ¿Cómo ha evolucionadoel número de créditos concedidos a lo largo del año 2018? ¿Y el volumen prestado?
  4. Trata de Obtener algún insight interesante del dataset y realiza una explicación detallada, apoyándote de las métricas y las representaciones gráficas que sean necesarias