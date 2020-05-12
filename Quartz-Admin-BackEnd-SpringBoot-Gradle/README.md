# Prepear

**DataBase**

setting datasource connection for MySQL.

default is localhost:3306

**Schema**

Confirm Quartz table is exists.
If not exists, need run script (quartz_innodb.sql & job_entity.sql) for create schema.

**Data**

Import initial data.

run script (job_entity.sql) to insert initial data.

# Compile

```
gradle bootJar
```

# Run

```
gradle bootRun
```


