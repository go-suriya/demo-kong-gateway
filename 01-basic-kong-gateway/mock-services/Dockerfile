FROM node:20

RUN apt-get update && apt-get install -y \
    curl \
    && curl -fsSL https://deb.nodesource.com/setup_20.x | bash - \
    && apt-get install -y nodejs

RUN npm install -g json-server@0.17.4

WORKDIR /data

EXPOSE 3030

CMD ["json-server", "/data/db.json", "-H=0.0.0.0", "-p=3000"]
