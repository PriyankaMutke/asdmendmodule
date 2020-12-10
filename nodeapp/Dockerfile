FROM node:7
WORKDIR /endmodule
COPY package.json /endmodule
RUN npm install
COPY . /app
CMD node server.js
EXPOSE 8081
