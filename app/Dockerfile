FROM node:14.1.0-alpine

WORKDIR /app

RUN apk update && \
    npm install -g npm && \
    npm install -g @vue/cli && \
    npm install -g @vue/cli-init && \
    npm install -g create-nuxt-app

ENV HOST 0.0.0.0

# COPY ./webapp/package.json /app/webapp/package.json
# COPY ./webapp/package-lock.json /app/webapp/package-lock.json
# RUN npm install

CMD ["npm", "run", "dev"]