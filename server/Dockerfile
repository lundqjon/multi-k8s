FROM node:16-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
ENV BROWSER=none
CMD ["npm", "run", "start"]
