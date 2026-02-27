FROM node:22
COPY ./ /react-hello2/frontend
WORKDIR /react-hello2/frontend
RUN npm install
EXPOSE 5173
ENTRYPOINT ["nmp", "run", "dev"]
