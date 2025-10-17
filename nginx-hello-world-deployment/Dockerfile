# Usa una imagen base de Ubuntu
FROM ubuntu:latest

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el código de la aplicación local al directorio /app del contenedor
COPY . .

# Instala el paquete curl
RUN apt-get update && apt-get install -y curl

# Expone el puerto 80 para que el contenedor pueda recibir peticiones
EXPOSE 80

# Comando que se ejecutará al iniciar el contenedor
CMD ["echo", "¡Hola from Ubuntu!"]
CMD ["tail", "-f", "/dev/null"]
