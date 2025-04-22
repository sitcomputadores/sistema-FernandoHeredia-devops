# Usar una imagen base de Java
FROM openjdk:17-jdk-slim

# Copiar el archivo JAR generado al contenedor
COPY target/config-server-0.0.1-SNAPSHOT.jar app.jar

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "/app.jar"]