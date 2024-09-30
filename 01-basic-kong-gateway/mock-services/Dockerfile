FROM node:16

RUN npm install -g json-server
WORKDIR /data

EXPOSE 3030
CMD ["json-server", "/data/db.json", "--host", "0.0.0.0", "--port", "3030"]
