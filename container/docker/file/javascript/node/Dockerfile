FROM node:22.13.1 AS build

LABEL author hieudoanm

RUN mkdir /home/node/app
WORKDIR /home/node/app

COPY . /home/node/app

RUN pnpm install & pnpm build

FROM node:22.13.1-alpine

USER node

COPY --from=build /home/node/app ./

ENV PORT=5000

EXPOSE $PORT

CMD ["yarn", "start"]
