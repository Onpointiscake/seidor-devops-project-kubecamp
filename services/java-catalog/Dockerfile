# Usa una imagen base de Java
FROM openjdk:11-jre-slim

# Establece el directorio de trabajo
WORKDIR /app

# Copia el código fuente a la imagen
COPY services/java-catalog /app

# Compila y ejecuta la aplicación
CMD ["java", "-jar", "nombre_del_archivo.jar"]