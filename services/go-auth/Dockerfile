# Usa una imagen base de Go
FROM golang:alpine

# Establece el directorio de trabajo
WORKDIR /app

# Copia el código fuente a la imagen
COPY services/go-auth /app

# Compila la aplicación
RUN go build -o go-auth

# Expón el puerto en el que se ejecutará la aplicación
EXPOSE 8080

# Comando para ejecutar la aplicación
CMD ["./go-auth"]
