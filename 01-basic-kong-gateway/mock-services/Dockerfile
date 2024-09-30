FROM node:18

RUN npm install -g json-server
WORKDIR /data

EXPOSE 3030
CMD ["json-server", "/data/db.json", "-H=0.0.0.0", "-p=3000"]
