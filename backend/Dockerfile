# Usa una imagen base de Node
FROM node:14

# Establece el directorio de trabajo
WORKDIR /app

# Copia los archivos necesarios
COPY package.json ./
COPY src ./src

# Instala las dependencias
RUN npm install

# Expone el puerto
EXPOSE 5000

# Comando para iniciar el servidor
CMD ["npm", "start"]
