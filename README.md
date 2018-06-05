# migrate
Projeto Migrate

1 - Criar database no mysql: create database app;
2 - Incluir scripts em src/main/resources/db/migration: V1__Create_person_table.sql
3 - Executar na linha de comando: mvn -Dflyway.configFile=database-homolog.properties flyway:migrate
