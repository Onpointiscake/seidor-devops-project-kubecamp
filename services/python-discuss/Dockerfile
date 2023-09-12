# Usa una imagen base de Python
FROM python:3.9

# Establece el directorio de trabajo
WORKDIR /app

# Copia el código fuente a la imagen
COPY services/python-discuss /app

# Instala las dependencias de Python si es necesario
# RUN pip install -r requirements.txt

# Comando para ejecutar la aplicación Python
CMD ["python", "app.py"]
