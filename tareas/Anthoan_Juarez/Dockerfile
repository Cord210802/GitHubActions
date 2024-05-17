# Usa una imagen base oficial de Python
FROM python:3.9-slim

# Establece el directorio de trabajo en /app
WORKDIR /app

# Copia el archivo de requerimientos en el contenedor de trabajo
COPY requirements.txt .

# Instala las dependencias
RUN pip install --no-cache-dir -r requirements.txt

# Copia el script en el contenedor de trabajo
COPY script.py .

# Ejecuta el script
CMD ["python", "script.py"]
