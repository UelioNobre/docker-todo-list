FROM node:14
WORKDIR /
EXPOSE 3001
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]