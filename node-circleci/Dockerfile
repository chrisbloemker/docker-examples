FROM node:10-alpine 
ENV NPM_CONFIG_LOGLEVEL warn
RUN mkdir -p /usr/src/app
EXPOSE 3000
WORKDIR /usr/src/app
ADD package.json /usr/src/app/
RUN npm install --production
ADD . /usr/src/app/
#RUN npm install && npm cache clean --force
CMD [ "npm", "start"]
