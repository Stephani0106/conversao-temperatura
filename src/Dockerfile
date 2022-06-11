FROM node:16.15.0

WORKDIR /app

# Copia os arquivos package-lock.json e package.json para o diretório atual
COPY ./package*.json ./

# Instala as dependências 
RUN npm install

# Copia os arquivos restantes do projeto para o diretório atual
COPY . ./

EXPOSE 8080

CMD ["node", "server.js"]
