# ------------------------------------------------
# -- GAS
# ------------------------------------------------

FROM node:18.7.0-buster-slim

WORKDIR /home/project

RUN apt-get update -y; \
    apt-get upgrade -y; \
    npm install -g npm@8.17.0 @google/clasp; \
    npm install

# COPY --chown=node:node package.json yarn.lock ./
# USER node

CMD ["tail", "-f", "/dev/null"]
