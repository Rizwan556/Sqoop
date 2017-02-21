# Sqoop
Sqoop workbench

//To import all the tables from mysql database called employee and importing in to hive warehouse as avro format
$ sqoop import-all-tables --connect jdbc:mysql://localhost/employee --username root --password mysql --as-avrodatafile --warehouse-dir /user/hive/warehouse/employee1.db --m 1

