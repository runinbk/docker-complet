# Utiliza una imagen base oficial de Python
FROM python:3.8-slim

# Establece el directorio de trabajo en el contenedor
WORKDIR /app

# Copia los archivos del directorio actual al directorio de trabajo en el contenedor
COPY . .

# Instala las dependencias
RUN pip install --no-cache-dir -r requirements.txt

# Expone el puerto en el que la aplicación correrá
EXPOSE 5000

# Comando para ejecutar la aplicación
CMD ["python", "app.py"]