FROM node:18

WORKDIR /app

ENV NODE_OPTIONS=--openssl-legacy-provider
ENV PORT=3000

COPY package.json package-lock.json ./

EXPOSE 3000

CMD ["serve","-s","build","-l","3000"]
