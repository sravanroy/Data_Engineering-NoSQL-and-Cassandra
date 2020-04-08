## Summary
* [ETL process](#ETL-process)
* [Project structure](#Project-structure)

--------------------------------------------

#### ETL process

Although this is not an ETL focused project, we must care how data will be <br> ingested in our database, and how to read our input properly. <br> Our ETL process consist in read every file in /event_data, this data have to be <br> aggregated in a file called event_datafile_new.csv and after the aggregation, <br>
 the file has to be parsed and persisted on the database

--------------------------------------------



#### Project structure
This is the project structure, if the bullet contains ``/`` <br>
means that the resource is a folder:

* <b> /event_data </b> - The directory of CSV files partitioned by date
* <b> /images </b> - Simply a folder with images that are used in Project_1B_ Project_Template notebook
* <b> Project_1B_ Project_Template.ipynb </b> - It is a notebook that illustrates the project step by step
* <b> event_datafile_new.csv </b> - The aggregated CSV composed by all event_data files

--------------------------------------------
