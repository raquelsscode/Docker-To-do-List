FROM node:14-alpine
WORKDIR /
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3001
CMD [ "npm", "start" ] 