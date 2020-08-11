FROM node

RUN mkdir -p /nuxt
COPY . /nuxt
WORKDIR /nuxt

RUN chmod u+x /usr/local/bin/yarn && \
    yarn global add nuxt && \
    yarn global add vue-cli create-nuxt-app@2.15

ENV HOST 0.0.0.0
EXPOSE 3000
CMD ["yarn", "start"]
