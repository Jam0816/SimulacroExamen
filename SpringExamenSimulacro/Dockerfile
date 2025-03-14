#java 17
FROM openjdk:17-jdk-slim

#directorio de trabajo en /app
WORKDIR /app

#copiar JAR
COPY target/SpringExamenSimulacro-0.0.1-SNAPSHOT.jar app.jar

#expone el puerto 8080
EXPOSE 8080

#ejecuta la aplicacion 
CMD [ "java", "-jar", "app.jar" ]
 