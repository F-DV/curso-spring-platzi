# curso-spring-platzi

- En el curso se creara un proyecto para gestionar todos los productos de un supermercado
- Utilizara el gestor de dependencias Gradle
- Proyecto tendra una arquitectura por capas orientado al dominio

# Configuracion Spring
- podemos Varios perfiles de Spring , el path de entrada, etc desde el archivo application.properties
- Es importante conservar la estructura del nombre del archivo
- Debemos tener un application.properties principal quien dira que perfil esta trabajando
- Documentación con Configuraciones de Spring: https://docs.spring.io/spring-boot/docs/current/reference/html/application-properties.html

# ¿Que es JPA?
- Es una especificación de java estandar para un framework ORM.
- Son una serie de reglas que java define para cualquier framework.
- Los framewroks mas populares para este fin son:
- Hibernate
- TopLink
- EclipseLink
- ObjectDB

# Spring Data
- Nos provee borrar registros, modificar registros, recuperar registros, etc, gracias a sus repositorios
- Nos permiten hacer todo tipo de operacion en bases de datos sin escribir una solo linea de codigo
- Nos proveen auditorias para saber cuando se actualizo algo en la base de datos.