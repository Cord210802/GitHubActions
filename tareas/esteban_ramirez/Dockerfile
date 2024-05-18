# Utiliza una imagen base oficial de Python
FROM python:3.9-slim

# Establece el directorio de trabajo
WORKDIR /app

# Copia el archivo de Python al contenedor
COPY codigo/script.py .

COPY requirements.txt .


# Instala las dependencias necesarias (añade las tuyas si es necesario)
RUN pip install -r requirements.txt

# Comando por defecto para ejecutar el archivo Python
CMD ["python", "script.py"]