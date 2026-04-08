#Imagen de Python Oficial
FROM python:3.9

#Directorio de trabajo
WORKDIR /app

#Copiar el archivo de dependencias
COPY requeriments.txt .
RUN pip install --no-cache-dir -r requeriments.txt

#Copiar el codigo al cotenedor
COPY . .

#Exponer el puerto 5000
EXPOSE 5000

#Ejecutar el flask
CMD ["python", "app.py"]
