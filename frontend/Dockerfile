FROM node:latest
WORKDIR /app
COPY ./frontend_notes/package.json ./
RUN npm install
COPY ./frontend_notes .
EXPOSE 3000
CMD ["npm", "start"]