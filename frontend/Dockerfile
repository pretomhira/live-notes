FROM node:latest
WORKDIR /app
COPY ./frontend_notes/package.json ./
RUN npm install
COPY ./frontend_notes .
CMD ["npm", "start"]