
FROM node:14
WORKDIR /app
COPY package.json package-lock.json ./
RUN npm install
COPY . .
# RUN sed -i 's/localhost:5000/<name of cluster ip>/g' *
RUN find /app -type f -exec sed -i 's/http:\/\/localhost:5000/https:\/\/dhanush.com/g' {} +
#localhost:5000
CMD ["npm", "start"]
