FROM node:14-buster
WORKDIR /usr/src/app

RUN npm install --save prop-types
RUN npm install -g create-react-app

# コンテナが停止しない様にbashを対話モードで起動
CMD sh -c "/bin/bash"