# springboot-generate-entity-from-database-tables

### Open eclipse editor
- new jpa project
- target runtime -> java
- platform - 2.1 Generic
- User Library -> manage library -> new -> user library name(eclipselink) -> select eclipselink -> add exteranl jar (eclipselink.jar + javax.persisitance_2.5.jar)
- Add connection -> new MySql -> add new driver -> MySql Database driver -> remove existing jar -> add exteranl MySql jar (mysql-connector.jar)
- configure Database connection
- finish

### Generate Enitiy class from Database Tables
- right click on model -> new -> JPA Entity from tables -> select Database connection -> select tables -> generate.

### Create Tables in Database from package
 - create table_name and fields -> generate Entity
 
 ### Generate Database tables form Entity (on start server will create the tables)
 - spring.jpa.hibernate.ddl-auto=create
 
  ### Update Database tables form Entity (on start server will update the tablesfields)
 - spring.jpa.hibernate.ddl-auto=update
 
 
