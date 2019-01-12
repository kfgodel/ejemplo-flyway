# Springboot Flyway example

(Text on this project is mostly in spanish)

Ejemplo basado en la documentacion de [esta pagina](https://www.callicoder.com/spring-boot-flyway-database-migration-example/)
con un setup inicial a mano (no incluido en la pagina).

#### Pasos seguidos
1. Crear el proyecto con [Spring Initialzr](https://start.spring.io/)
  - Indicar que es proyecto con jpa, flyway y postgres como base
2. Crear el compose para una base postgres contenida
3. Modificar el [application.properties](src/main/resources/application.properties) para apuntar a la base
4. Agregar [config de logback](src/main/resources/logback.xml) para mejorar el output
5. Agregar [primer script](src/main/resources/db/migration/V1__init.sql) de migracion (usando version)
   