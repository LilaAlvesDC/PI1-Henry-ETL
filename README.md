# TRABAJO INDIVIDUAL DE ETL 

El trabajo consiste en procesar varios dataset de diversos formatos, transformar los datos para extraer dato valioso y finalmente generar un archivo de SQL para su posterior carga en cualquier DataLake en un workflow. 

Podes acceder a la consigna completa en el siguiente: [Link](https://github.com/soyHenry/PI01_DATA_ENGINEERING "Link")

## Tecnologías 

Para la elaboración de este workflow se utilizó principalmente **Python** con las siguiente librerías: 
- *Jupyter* - Interfaz 
- *Pandas* - Para manipulación de datos
- *Pathlib* - Para gestión de path 
- *Chardet* - Para identificar el encoding de los archivos 
- *re* - Para gestión de las expresiones regulares
- *mysql.connector *- Para conectar y gestionar base de datos en mySQL

[![Archivos](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/1%20Archivos.JPG "Archivos")](https://github.com/LilaAlvesDC/workflow_ETL/blob/main/_str/1%20Archivos.JPG "Archivos")


# ¿Cómo correr el script en línea usando solo Google Colab? 

1. Para correr el script en línea primero deberás crear un acceso directo a los datasets usando google drive. Para hacerlo acceder al siguiente [Link](http://drive.google.com/drive/folders/1Rsq-HHomPtQwy7RIWQ574wKcf56LiGq1 "Link") 

2. Luego podes acceder al siguiente [Notebook](https://colab.research.google.com/drive/17YMz4FL8vhD23dS5F3eX6cSC6mUJIgMC?usp=sharing "Notebook") en línea.

3. En la celda #2 deberás conceder permisos para que tu cuenta de google drive pueda tener acceso a los datasets enviados. 

4. Finalmente podrás seguir todo el flujo de trabajo hasta la exportación de los datasets limpios.

**Nota:** Para realizar el último paso donde cargas los datos en el DataLake mediante los archivos SQL deberás descargar los archivos ubicados en: , luego ejecutarlos en tu workbench de preferencia y finalmente tendrás creada una base de datos con los datasets enviados.

### Colaboradores

- [Chybeat](https://github.com/chybeat)
- [root@spyro:~#](https://github.com/rootspyro)
- [milord](https://github.com/milord)
