# FROM nginx
# COPY build /usr/share/nginx/html

FROM node:17
WORKDIR /app
COPY . .
RUN npm install --force
EXPOSE 3000
ENTRYPOINT ["npm", "start"]

