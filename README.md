# TRABAJO INDIVIDUAL DE ETL 


[<img src="https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/5.%20ETL.png">](https://www.youtube.com/embed/oMUfQsOVToI "ETL: 55")

El trabajo consiste en procesar varios dataset de diversos formatos, transformar los datos para extraer dato valioso y finalmente generar un archivo de SQL para su posterior carga en cualquier DataLake en un workflow. 

Podes acceder a la consigna completa en el siguiente: [link](https://github.com/soyHenry/PI01_DATA_ENGINEERING "Link")

El workflow de ETL consiste en tres etapas: Extracción, Tranformación y Carga como sigue en la siguiente imagen. 

[![Proceso de ETL](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/3.%20Workflow.jpg "Proceso de ETL" )](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/3.%20Workflow.jpg "Proceso de ETL")

## Tecnologías 

Para la elaboración de este workflow se utilizó principalmente **Python** con las siguiente librerías: 
- *Jupyter* - Interfaz 
- *Pandas* - Para manipulación de datos
- *Pathlib* - Para gestión de path 
- *Chardet* - Para identificar el encoding de los archivos 
- *re* - Para gestión de las expresiones regulares
- *mysql.connector* - Para conectar y gestionar base de datos en mySQL

### Archivos Originales

[![Archivos](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/1%20Archivos.JPG "Archivos")](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/1%20Archivos.JPG "Archivos")


# ¿Cómo correr el script en línea usando solo Google Colab? 

1. Para correr el script en línea primero deberás crear un acceso directo a los datasets usando google drive. Para hacerlo acceder al siguiente [link](http://drive.google.com/drive/folders/1Rsq-HHomPtQwy7RIWQ574wKcf56LiGq1 "link") 

[![Añadir acceso directo](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/2%20A%C3%B1adir%20acceso%20directo.jpg "Añadir acceso directo")](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/2%20A%C3%B1adir%20acceso%20directo.jpg "Añadir acceso directo")

2. Luego podes acceder al siguiente [notebook](https://colab.research.google.com/drive/17YMz4FL8vhD23dS5F3eX6cSC6mUJIgMC?usp=sharing "notebook") en línea.

3. En la celda #2 deberás conceder permisos para que tu cuenta de google drive pueda tener acceso a los datasets enviados. 

4. Finalmente podrás seguir todo el flujo de trabajo hasta la exportación de los datasets limpios.

**Nota:** Para realizar el último paso donde cargas los datos en el DataLake mediante los archivos SQL deberás descargar los archivos ubicados en: [archivos SQL](https://github.com/LilaAlvesDC/workflow_ETL/upload/main/Archivos%20SQL "Archivos SQL"), luego ejecutarlos en tu workbench de preferencia y finalmente tendrás creada una base de datos con los datasets enviados.

Finalmente creamos una base de datos con el siguiente Diagrama ER: 

[![Diagrama ER](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/4.%20Diagrame%20ER.jpeg "Diagrama ER")](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/4.%20Diagrame%20ER.jpeg "Diagrama ER")

¡Gracias a quienes hicieron posible este proyecto! 

