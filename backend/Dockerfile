FROM node:20-alpine
WORKDIR /app-backend
RUN npm install -g json-server
COPY src/jobs.json ./
EXPOSE 8000
CMD ["json-server", "--watch", "jobs.json", "--port", "8000"]
