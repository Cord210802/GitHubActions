# Usa una imagen base de Python
FROM python:3

# Establece el directorio de trabajo en /app
WORKDIR /app

# Copia el archivo .py al contenedor en el directorio /app
COPY prueba.py /app

# Instala las dependencias necesarias
RUN pip install polars pandas

# Ejecuta el archivo .py cuando se inicie el contenedor
CMD ["python", "prueba.py"]
