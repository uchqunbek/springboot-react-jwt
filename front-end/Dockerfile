FROM node:10-alpine
ADD app-react /opt/app-react
WORKDIR /opt/app-react
RUN npm install
RUN npm run build-prod
EXPOSE 8080
CMD ["npm", "run", "dev"]