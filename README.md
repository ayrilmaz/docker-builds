# docker-builds

Build image and publish to docker hub

sample

```
FROM node:14

ENV TZ=Europe/Istanbul

RUN npm i -g @angular/cli@13
RUN mkdir /home/app && chown node:node /home/app

#docker build -t ng13 .
#docker tag ng13 ayrilmaz/ng13
#docker push ayrilmaz/ng13
```
