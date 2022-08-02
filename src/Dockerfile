# Boas práticas - Sempre definir a versão da base para garantir que a aplicação sempre executará bem
# Boas prátivas - Criar arquivo .dockerignore com os arquivos/diretórios que não devem fazer parte da imagem
FROM node:16
WORKDIR /app
COPY ./package*.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
