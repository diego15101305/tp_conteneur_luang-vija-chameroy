FROM node:22
COPY ./ /react-hello2/backend
WORKDIR /react-hello2/backend
RUN npm install
RUN npm run build
ENTRYPOINT ["nmp", "run", "dev"]
