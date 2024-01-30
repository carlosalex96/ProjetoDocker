# Imagem base com suporte ao aplicativo (Node.js, neste exemplo)
FROM node:latest

# diretório de trabalho dentro do contêiner
WORKDIR /app

# Copie os arquivos necessários para o contêiner
COPY . .

# Instale as dependências do aplicativo
RUN npm install nodemon --save-dev

# Comando para iniciar o aplicativo quando o contêiner for iniciado
CMD ["node", "app.js"]
