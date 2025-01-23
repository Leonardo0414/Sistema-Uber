# FROM node:20-slim

# # Instalando dependências necessárias
# RUN apt-get update -y && apt-get install -y openssl procps

# WORKDIR /home/node/app

# # Configurar permissões corretas
# COPY --chown=node:node package*.json ./
# COPY --chown=node:node prisma ./prisma/
# COPY --chown=node:node . .

# USER node

# # Instalação de dependências
# RUN npm install
# RUN npx prisma generate

# EXPOSE 3000

# CMD [ "tail", "-f", "/dev/null" ]


#VERSAO ANTIGA
 FROM node:20-slim

RUN apt-get update -y && apt-get install -y openssl procps

WORKDIR /home/node/app

USER node

CMD [ "tail", "-f", "/dev/null"	 ]