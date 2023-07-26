FROM node:14
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install -f
COPY . .
RUN sed -i 's/"dbhost":"20.127.252.227"/"dbhost":"mysql-service"/g' ./lib/config.json
# RUN sed -i 's/"host":"localhost"/"host":"nodejs-container"/g' ./lib/config.json
CMD ["node", "index.js"]
