FROM node:22
COPY ./ /react-hello
WORKDIR /react-hello
RUN ls
RUN npm install
EXPOSE 5173
ENTRYPOINT ["npm", "run", "dev"]
